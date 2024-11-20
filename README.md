---
# Pràctica d'Identificació de Components de la Placa Base
---

## Components Identificats

### 1. **Processador (CPU) i Sòcol Correspondent**
   - **Ubicació**: Normalment al centre de la placa base.
   - **Funció**: El processador és el cervell de l'ordinador. És responsable de processar totes les instruccions i realitzar els càlculs necessaris per al funcionament del sistema. El sòcol és el component on s'instal·la la CPU, connectant-la amb la resta de la placa base.
   - **Tipus**: Depèn de la marca i model, poden ser Intel o AMD.

### 2. **Xipset (Northbridge i Southbridge)**
   - **Ubicació**: El Northbridge sol estar a prop de la CPU, mentre que el Southbridge es troba més a baix a la placa base.
   - **Funció**: El chipset és un conjunt de circuits que gestiona la comunicació entre la CPU, la memòria RAM, els dispositius d'emmagatzematge i altres components perifèrics. 
     - **Northbridge**: Gestiona connexions ràpides, com la comunicació amb la memòria RAM i la targeta gràfica.
     - **Southbridge**: Gestiona connexions més lentes, com ports USB i dispositius d'emmagatzematge.

### 3. **Ranures de Memòria RAM**
   - **Ubicació**: Són les ranures llargues que es troben generalment al costat de la CPU.
   - **Funció**: Permeten instal·lar la memòria RAM, que és utilitzada per emmagatzemar temporalment dades i programes que la CPU necessita mentre treballa. 
   - **Tipus de Memòria**: DDR4, DDR5, depenent de la compatibilitat de la placa base.

### 4. **BIOS/UEFI (xip de firmware)**
   - **Ubicació**: A prop de la CPU.
   - **Funció**: El BIOS o UEFI és el sistema que gestiona l'inici del sistema operatiu. S'encarrega de comprovar els components bàsics de l'ordinador abans d'iniciar el sistema. També emmagatzema la configuració de la placa base.

### 5. **Ranures d'Expansió (PCI, PCIe)**
   - **Ubicació**: Generalment es troben a la part inferior de la placa base.
   - **Funció**: Permeten afegir targetes d'expansió com targetes gràfiques, de so, o de xarxa.
   - **Tipus**: PCIe (Peripheral Component Interconnect Express) és el més modern i ofereix velocitats de transferència més altes.

### 6. **Connexions de la Font d'Alimentació**
   - **Ubicació**: Normalment a la part superior de la placa base.
   - **Funció**: Permeten connectar l'ordinador a la font d'alimentació, que proporciona energia a tots els components del sistema.
   - **Tipus de Connectors**: Connectors de 24 pins per a la placa base i connectors de 4 o 8 pins per a la CPU.

### 7. **Ports d'Emmagatzematge (SATA, NVMe)**
   - **Ubicació**: Prop de les ranures de memòria o a prop de la CPU, depenent del model.
   - **Funció**: Permeten connectar dispositius d'emmagatzematge com discs durs i SSDs.
     - **SATA**: Utilitzat per discos durs i SSDs més antics.
     - **NVMe**: Utilitzat per SSDs de major velocitat.

### 8. **Port de Xarxa Ethernet**
   - **Ubicació**: Generalment a la part posterior de la placa base.
   - **Funció**: Permet connectar l'ordinador a una xarxa local per accedir a Internet o comunicar-se amb altres dispositius.

### 9. **Conectors Externs i Interns (USB, HDMI, etc.)**
   - **Ubicació**: Ports USB externs estan a la part posterior de la placa base. Ports interns com USB frontals o connectors de àudio es troben a la part inferior.
   - **Funció**: Permeten connectar dispositius externs com teclats, ratolins, monitor, etc.

### 10. **Pila de la BIOS**
   - **Ubicació**: A prop del xip BIOS/UEFI.
   - **Funció**: Manté les configuracions del sistema (com la data i hora) quan l'ordinador està apagat.

## Esquema de la Placa Base

<img src="https://github.com/awpzz/Placa-Base/blob/main/placa%20base.jpg" alt="Esquema de la Placa Base">

## Interacció entre Components

1. **CPU i Memòria RAM**: 
   La CPU utilitza la RAM per emmagatzemar dades temporals que necessita durant l'execució dels programes. La comunicació entre ambdós és essencial perquè la CPU pugui treballar de manera eficient.

2. **Chipset i Memòria RAM**:
   El chipset gestiona les comunicacions entre la CPU i la RAM. El **Northbridge** s'encarrega de les connexions ràpides entre la CPU i la memòria, mentre que el **Southbridge** facilita les connexions més lentes.

3. **CPU i Dispositius d'Emmagatzematge**:
   Quan la CPU necessita accedir a dades, primer consulta la RAM. Si les dades no es troben a la RAM, la CPU accedeix als dispositius d'emmagatzematge (SATA o NVMe), amb l'ajuda del chipset, per obtenir la informació.
