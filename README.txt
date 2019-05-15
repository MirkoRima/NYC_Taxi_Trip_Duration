ADVANCE MACHINE LEARNING
NYC - TAXI TRIP DURATION  

Pennati Mattia  	793375
Rima Mirko  		793435
Rovera Francesco  	794194



ISTRUZIONI:

Prima di eseguire ciascuno scrip importare la cartella condivisa all'interno del proprio Drive e verificare, nella fase di import
dei file .csv, che i percorsi siano quelli corretti.



DESCRIZIONE DIRECTORY:

Nella directory troverete una cartella denominata Datset contenente appunto i dataset di partenza e il dataset finale.
Oltre ai dataset troverete anche 4 nootebook python ognuno dei quali con uno scopo specifico:

1_DataProcessing: 		script responsabile della creazione, mediante le operazioni descritte nel capitolo 2 della relazione, 
		  		del dataset su cui verranno applicati i modelli di ML

2_TripDuration(Discrete): 	script che contiene tutta la parte relativa alla creazione di un modello che si occupa della
				classificazione della variabile target in un intervallo discreto.
				Classi: 
					0 -> Viaggio breve (<5 min)
					1 -> Viaggio medio-breve (tra 5 e 10 min)
					2 -> Viaggio medio (tra 10 e 25 min)	
					3 -> Viaggio medio-lungo(tra 25 e 40 min)
					4 -> Viaggio lungo(tra 40 e 120 min)

3_TripDuration(Continuous):	script che contiene tutta la parte relativa alla creazione e ottimizzazione di un modello che si
				occupa della preizione della variabile target all'interno di un intervallo continuo.

4_TripDuration(InitialDataset): script che crea entrambi i modelli (classificatore e regressore) utilizzando i parametri ottimizzati 
				(ottenuti dagli script 2 e 3) ma utilizza il dataset di partenza (10 features) e non quello 
				ottenuto dall'esecuzione dello script "1_DataProcessing"

 

