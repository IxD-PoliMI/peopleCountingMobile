# People Counting Mobile
Author: [Emanuele Della Valle](http://emanueledellavalle.org/) and [ChatGPT 4.0](https://chat.openai.com/share/88a557a8-88e6-4cd3-907c-d8046d05eeae)

This repo demonstrates how to make a minimal Mobile Web-based application that uses Edge Impulse's [WASM](https://webassembly.org/) package to count people (actually, characters for plastic models) in a room viewed by a ceiling camera. It runs on your mobile. The WASM package includes a [FOMO (Faster Objects, More Objects) MobileNetV2 0.35](https://docs.edgeimpulse.com/docs/edge-impulse-studio/learning-blocks/object-detection/fomo-object-detection-for-constrained-devices) finetuned on [Edge Impulse](https://studio.edgeimpulse.com/public/357387/live). 

Hereafter, you find an example of the images it takes as input.

<img width="556" alt="image" src="https://github.com/IxD-PoliMI/peopleCounting/assets/5645019/aa42bfff-c213-4a86-a1f2-5b52714f5aee">

It is the result of merging:
- The work published in the [people counting repo](https://github.com/IxD-PoliMI/peopleCounting)
- The work published in the [webcam-js repo](https://github.com/IxD-PoliMI/webcam-js)
- The code of (Edge Impulse's mobile client](https://docs.edgeimpulse.com/docs/edge-ai-hardware/using-your-mobile-phone), in particular the [js library to access the camera](https://github.com/edgeimpulse/mobile-client/blob/master/client/sensors/camera.ts)
- Many good answers from Stackoverflow, such as [this one](https://stackoverflow.com/questions/42866508/how-can-i-open-rear-camera-in-mobile-device-using-webcam-js)

# Contapersone per cellulare
Autore: [Emanuele Della Valle](http://emanueledellavalle.org/) e [ChatGPT 4.0](https://chat.openai.com/share/88a557a8-88e6-4cd3-907c-d8046d05eeae)

Questo repo mostra come realizzare un'applicazione minimale basata sul Web mobile che utilizza il pacchetto [WASM](https://webassembly.org/) di Edge Impulse per contare le persone (in realtà, personaggi per modelli di plastica) in una stanza vista da una telecamera a soffitto. Funziona sul vostro cellulare. Il pacchetto WASM include una [FOMO (Faster Objects, More Objects) MobileNetV2 0.35](https://docs.edgeimpulse.com/docs/edge-impulse-studio/learning-blocks/object-detection/fomo-object-detection-for-constrained-devices) messa a punto su [Edge Impulse](https://studio.edgeimpulse.com/public/357387/live). 

Di seguito, un esempio delle immagini che prende in input.

<img width="556" alt="image" src="https://github.com/IxD-PoliMI/peopleCounting/assets/5645019/aa42bfff-c213-4a86-a1f2-5b52714f5aee">

È il risultato della fusione:
- Il lavoro pubblicato nella repo [people counting repo](https://github.com/IxD-PoliMI/peopleCounting)
- Il lavoro pubblicato nella [webcam-js repo](https://github.com/IxD-PoliMI/webcam-js)
- Il codice di (client mobile di Edge Impulse](https://docs.edgeimpulse.com/docs/edge-ai-hardware/using-your-mobile-phone), in particolare la [libreria js per accedere alla fotocamera](https://github.com/edgeimpulse/mobile-client/blob/master/client/sensors/camera.ts)
- Molte buone risposte da Stackoverflow, come [questa]([https://stackoverflow.com/questions/428](https://stackoverflow.com/questions/42866508/how-can-i-open-rear-camera-in-mobile-device-using-webcam-js)https://stackoverflow.com/questions/42866508/how-can-i-open-rear-camera-in-mobile-device-using-webcam-js)
