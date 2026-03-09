# TLS_Covertor_Upgrade


<h2>Description </h2>

    - This project entails the process of upgrading from Secure Socet Layer (SSL) to Transport Layer Security (TLS). Both are cryptograhic protocols designed to provide secure commnucation over a computer network.
    - Secure Socet Layer has been one of the most widely-used encryption protocols. It remains use today despiste the existence of a number of known security vulnerabilities and despite being deprecated by NIST in 2014
    - According to NIST, there are no fixes or patches that can adequately repair SSL, therefore it is critically important that organization upgrade to secure alternative which is TLS 1.2 protocol.
    - Payment Card Industry (PCI) manadated that all processing and third party entities- including Acquirers, Processors, Gateway, and Service Providers must provide TLS1.1 or greater service offering. 
    - PCI also required that all entities  must cutover to use  ONLY a secure version of TLS (as defined by NIST).
    
        
         
<h2>Operating System Used </h2>

         - Vmare Workstation (Production Environment)
         - Windows 10 Pro

<h2> Check Screenshots below: </h2>

 - Screenshot 1- Firewall Requirements (Global Port Requirments & Pinpad Support)
 - Transaction Link Production (API)

<img width="698" height="825" alt="Screenshot_3_Firewall_Requirement" src="https://github.com/user-attachments/assets/c6665b6a-ceec-46c3-9c6a-6e7d650e847b" />

    - Firewall Configuration for Transaction Link > V2.15.TL4


 - Screenshot 2- TLS Convertor Diagram

<img width="1206" height="516" alt="Screenshot_2_TLS_Converter_Diagram" src="https://github.com/user-attachments/assets/af532e04-cd88-4ab6-bd31-5ee56fef4390" />


      - Modify host name files on workstations 
      - Reconfigure the application using tv1/2 or g1/2 to convertor
      - Recceives < TLS1.2 and converts to TLS 1.2
      - Establish secure tunnel to ML cloud over TLS 1.2 
      - Validates connection request TLS 1.2 and SHA2 mutual authentication
      - Receives transactiion over TLS1.2 Process Transaction
      - Sends response over TLS1.2 to coverter 
    

 - Screenshot 3 - How to Check the RES version in Windows
   
<img width="508" height="646" alt="Screenshot_1_Determine_RES_Version" src="https://github.com/user-attachments/assets/30a049a7-5692-4a1f-aca9-9338754090f2" />

      - Navigate to the following path- C\Micros\REs\Pos\Bin
      - Right click on poscfg.exe
      - Nagigate down to Properties
      - Click on the Details View
      - Product Version will be listed in the Product Version Section.

 - Screenshot 4 - How to Check the RES version for Micros in Windows
 
<img width="357" height="300" alt="Screenshot_6_Micros" src="https://github.com/user-attachments/assets/9e23bb4b-d934-4c11-ba1d-985719752c2d" />

      - Log into the POS Configurator 
      - Click on the start window
      - Search POS configurator and launch the program at the top.
      - Click Help > About the POS configurator
      - The version will be displayed in the center of the page POS configuration : (Version 5.5 MR2)



 - Screenshot 5 - List of Restaurant Point of Sale Systems

<img width="540" height="649" alt="Screenshot_5_Retail POS Ssystem" src="https://github.com/user-attachments/assets/44f8495d-f1b7-4201-b80e-4ef9f3bcc9f1" />

     - Listed: MICROS 3700 and Micros e7

 
 - Screenshot 6 - List of Property Management and Reservations Systems

<img width="535" height="616" alt="Screenshot_4_PMS" src="https://github.com/user-attachments/assets/3827ac13-b003-4fa5-8e22-472464d6f117" />

     - Listed: Oracle Hospilitatlity  Opera Enterprise Scale Property Managment System

