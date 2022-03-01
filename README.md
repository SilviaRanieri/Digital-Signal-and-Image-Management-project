# Digital-Signal-and-Image-Management-project
Nel seguente progetto dedicato alla materia Digital Signal and Image Mana- gement, sono stati studiati diversi approcci per 3 tipi di problemi differenti:
# • Processing di segnali mono-dimensionali:
si tratta di un task di speaker re- cognition, i quali speaker da riconoscere sono i 3 membri del gruppo. Il problema `e stato affrontato allenando una semplice rete neurale fully-connected con spezzoni da un secondo di diverse registrazioni appartenenti ai 3 speaker da riconoscere. 
# • Processing di segnali bi-dimensionali: 
si tratta di un task di face recognition, i quali visi da riconoscere sono anche in questo caso quelli dei membri del gruppo. L’approccio al problema si `e basato sulla libreria OpenCV per la face detection e il successivo allenamento di una rete neurale convoluzionale tramite transfer learning e fine tuning. La face recognition `e stata successivamente implementata in real- time a video, la quale ha dimostrato robustezza anche in diverse condizioni di luce, espressioni e angolazioni diverse. 
# • Content based image retrieval: 
in questa ultima parte, l’obiettivo `e stato quello di restituire 10 volti piu` simili ad un volto dato come input, estrapolandoli da un ampio dataset di foto di celebrit`a. Per raggiungere l’obiettivo si `e fatto uso una seconda volta della libreria OpenCV per la face detection, i visi sono stati utilizzati per allenare un autoencoder, dal quale `e stata estratta la parte di encoding da utilizzare come feature extraction per le foto. Per trovare i volti piu` simili quindi si `e misurata la distanza tra le feature delle varie foto del dataset e quella di query.

# Software 
Abbiamo usato python per questo progetto.

# Team 
Mattia Boller m.boller@campus.unimib.it 

Raffaele Moretti r.moretti8@campus.unimib.it 

Silvia Ranieri s.ranieri7@campus.unimib.it
