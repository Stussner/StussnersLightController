# StussnersLightController
An Application for professional use in live Music Events to controll Light Shows and more



    This application analyzes audio signals in real time
    and converts them into a user-defined set of analog signals
    to synchronize the numerous and diverse devices used at live music events
    with the music.
  
    The widely used DMX standard is not suitable for this and is generally too static and inflexible.
    Therefore, even at large and expensive events, control is still asynchronous, which is a real shame.
    Because the synchronization of light and music has a major psychoacoustic and psychooptical impact.
  
    However, devices with an analog interface can be used, as is the case with the ILDA standard.
    The standard Ethernet protocol (sp2) should be used for data transmission,
    so that devices with a suitable analog signal interface
    can be integrated into the control network in a local network via a small hardware adapter.
    This means that the actuators are located in a LAN or WLAN, using the ESP32 microcontroller.
    Unfortunately, I can only create a few prototypes for testing.
    Developing and producing these would have to be done by other companies. 
  
    It is particularly important to ensure a simplified and largely automated application for users,
    so that complex and specific programming of the actuators can be avoided if necessary.
    For example, by providing a rough description of which style of music is assigned to which style of actuator.
    The exact style of music or the selection of music tracks is often unknown in advance.
    For example, when DJs make guest appearances at festivals or in discos, complex, specific programming is impractical.
    Nevertheless, the possibility should exist.
  
    In addition to very solid, clean beat type and tempo detection, a more complex analysis and interpretation of the frequency spectrum is required
    so that the spectrum's characteristics can be assigned to the characteristics of specific instruments and sound styles.
    The total latency of the audio signal until the converted analog signals are executed by the actuator must not exceed 10-30 milliseconds.
    This means the total latency: From the moment the audio signal is generated in the media player or the instrument played by a musician
    to the change in the actuator, which then typically changes light intensity, colors, movement patterns, and the like.
    Nevertheless, an abstract, generalized declaration and definition of actuator properties is required, as there are many different types.
    
----

    Diese Anwendung analysiert Audio Signale in Echtzeit 
    und wandelt diese in ein beutzerdefinierten Satz analoger Signale um , 
    um die zahlreichen und sehr verschiedenen Geräte, die bei live Musik Veranstaltungen benutzt werden,
    mit der Musik zu synchronisieren. 
  
    Der häufig benutzte DMX Standard ist hierfür nicht geeignet und generell zu statisch und zu unflexibel.
    Deshalb ist gegenwärtig, selbst bei riesigen und teuren Veranstaltungen die Steuerung immernoch asynchron, was erigentlich schade ist.
    Denn die Synchronisierung von Licht und Musik hat großen "psachoakutischen und psychooptischen" Einfluss.
    
    Aber es können Geräte mit einer Analogen Schnittstelle benutzt werden , wie es bei dem ILDA Standard der Fall ist.
    Für die Datenübertragung soll das normale Ethernet Protkoll (sp2) benutzt werden,
    so dass die Geräte, welche eine geeignete Analogsiggnal Schnittstelle besitzen, 
    in einem lokalen Netzwerk über eine kleinen Hardware Apapter in das Steuerungsnetzwerk eingebunden werden.
    Das heißt die AKtoren befinden sich in einem LAN oder in einem WLAN, unter Verwendung des ESP32 Mikrocontrollers.
    Ich kann leider nur ein paar Prototypen dessen umsetzen, zum testen. 
    Entwickeln und Produzieren müßten das andere Unternehmen, die Hardware bzw. Geräteentwicklung betreiben.
  
    Besonders wichtig ist es, den Benutzern ein erleichtert und weitgehend automatisierte ANwendung zu gewährleisten,
    damit eine aufwendige und konkrete Programmierung der Aktoren bei Bedarf umgangen werden kann.
    ZUm Beispiel durch eine grobe Beschreibung welchem Stil der Musik welchem Stil der AKtoren zugeordnet wird.
    Der genaue Stil der Musik beziehnungsweise die Auswahl der Musikstücke ist vorher oft nicht bekannt.
    Beispielsweise wenn Djs Gastauftritte bei Festivals oder in Diskotheken haben, dann ist eine aufwendige konkrete Programmierung unpraktisch.
    Dennoch sollte es die Möglichkeit geben.
  
    Neben der sehr soliden, sauberen Takterkennung, ist eine aufwendigere Anaylse und Interpretation des Frequenzspektrum erforderlich,
    damit die Charaktistik des Spektrums der Charakteristik bestimmter Instrumente und Soundsstile zugeordnet werden kann.
    Die Gesamtlatenz des Audiosignals bis zur Ausführung der konvertierten analogSignale Aktor darf 10-30 Millisekunden nicht überschreiten.
    Das meint also die Gesamtlatenz, 
    vom Moment der Erzeugung des Audiosignals im Mediaplayer oder dem gespielten Instrument eines Musikers,
    bis zur Veränderung im Aktor, welcher dann üblicherweise LIchtintensität, Farben , Bewegungmuster und ähnliches verändert.
    Dennoch ist eine abstrakte, verallgemeinerte Deklaration und Definition der AKtoreigenschaften erforderlich, denn es gibt sehr viele veschiedenen Typs.
  
  
  
  

  
  
