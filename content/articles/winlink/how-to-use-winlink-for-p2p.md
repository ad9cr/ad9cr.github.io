+++
title = 'How to Use Winlink for Peer to Peer Connections'
linkTitle = 'How to Use Winlink for Peer to Peer Connections'
summary = 'In this article, I will show you how to use Winlink Express to connect directly to other Winlink Express or Airmail clients via radio frequencies, without relying on the Winlink Hybrid Network or the internet. This is called peer-to-peer connectivity, and it can be useful for local or regional communication, as well as for testing and experimenting with different modes and frequencies.'
weight = 5
categories = ['Modes']
date = '2024-01-22'
tags = ['winlink', 'digital-modes']
+++

# How to Use Winlink for Peer to Peer Connections
In the previous articles, I introduced you to Winlink, a global radio email system that allows users to exchange messages with attachments, position reports, weather bulletins, emergency and relief communications, and more. I also explored the benefits of using Winlink for radio email communication, especially in situations where the internet is not available or reliable. I also showed you how to use Winlink Express, the most popular client software for Winlink, to connect to the Winlink Hybrid Network via radio message servers (RMS).

In this article, I will show you how to use Winlink Express to connect directly to other Winlink Express or Airmail clients via radio frequencies, without relying on the Winlink Hybrid Network or the internet. This is called peer-to-peer connectivity, and it can be useful for local or regional communication, as well as for testing and experimenting with different modes and frequencies.

## What is peer-to-peer connectivity?
Peer-to-peer connectivity is a mode of operation that allows two Winlink users to exchange messages directly via radio, without using any intermediate RMS or CMS stations. This means that the users do not need to have an internet connection or access to the Winlink Hybrid Network to communicate with each other. Peer-to-peer connectivity can also be faster and more efficient than using RMS stations, as it eliminates the need for store-and-forward and relay operations.

Peer-to-peer connectivity can be done using any of the supported modes and frequencies of Winlink, such as HF, VHF, UHF, or satellite, and PACTOR, WINMOR, VARA, ARDOP, or Packet. However, some modes and frequencies may be more suitable than others, depending on the distance, propagation, and bandwidth of the radio link. For example, HF modes may be better for long-distance communication, while VHF or UHF modes may be better for short-distance communication.

Peer-to-peer connectivity can also be done using any of the supported client software of Winlink, such as Winlink Express or Airmail. However, some client software may have more features and options than others, depending on the mode and frequency of the radio link. For example, Winlink Express has a built-in Winmor TNC and a channel selection tool, while Airmail has a built-in PACTOR TNC and a propagation prediction tool.

## How to set up peer-to-peer connectivity?
To set up peer-to-peer connectivity, you will need the following:

- A computer running Windows 7 or later, with at least 1 GB of RAM and 100 MB of free disk space.
- A valid amateur radio license, or a license or authorization from a participating government service or agency.
- A radio transceiver capable of operating on the desired mode and frequency, such as HF, VHF, UHF, or satellite.
- An interface device that connects your radio to your computer’s sound card or USB port, such as the Signalink, the Rigblaster, or the built-in sound card interface of some radios. This device will handle the audio signals and the push-to-talk function for your radio.
- A virtual TNC software that communicates with your interface device and Winlink Express, such as SoundModem by UZ7HO, Direwolf, or the built-in Winmor TNC of Winlink Express. This software will handle the data conversion and packet creation for Winlink.
- A Winlink Express or Airmail software that allows you to compose, send, and receive messages, as well as to configure and control your radio and virtual TNC. You can download the latest version of Winlink Express from winlink.org or Airmail from siriuscyber.net and run the installer. Follow the instructions to complete the installation.
- A peer station that is also using Winlink Express or Airmail, and is capable of operating on the same mode and frequency as you. You will need to know the callsign and the frequency of the peer station, as well as the time and duration of the peer-to-peer session.

## How to conduct peer-to-peer connectivity?
To conduct peer-to-peer connectivity, you will need to follow these steps:

- Launch Winlink Express or Airmail and enter your callsign and password. If you do not have a password, leave it blank and one will be assigned to you after your first connection. You can also enter your grid square and recovery email address for your account settings.
- Choose the mode of operation from the drop-down menu on the top left corner of the window. For this article, I will use Winmor Winlink, which is a data mode for HF radio. You can also choose other modes, such as Packet Winlink, Pactor Winlink, or Vara Winlink, depending on your equipment and preference.
- Open a session by clicking on the Open Session button on the top right corner of the window. This will open a new window where you can see the status and progress of your connection. You will also see an icon down in the taskbar for your virtual TNC software, such as SoundModem, Direwolf, or Winmor TNC. Click on it (or Alt-Tab to it) and another window will open up that shows the waterfall, meter dials and transmission speed for the session once underway, along with other information.
- Tune your radio to the frequency of the peer station, and adjust your interface device and virtual TNC software settings to optimize your radio communication. You will need to set the audio levels, the modulation mode, the baud rate, the frequency correction, and other parameters according to your radio and interface device specifications. You can also use the Test and Tune function of Winlink Express or Airmail to test your radio connection and adjust your settings accordingly.
- Compose a new message by clicking on the New Message button on the main window, or reply to an existing message by double-clicking on it. You can send and receive messages to and from other callsigns or email addresses, as well as request weather bulletins, position reports, and other services. You can also use various forms, such as ICS, HICS, Red Cross, and more, to facilitate standardized and efficient communication. Make sure to select Peer-to-Peer Message in the “Send As” window, and enter the callsign of the peer station in the “To” field. You may not send a CC: in this mode. Write the message as normal and select Post to Outbox.
- Initiate the peer-to-peer connection by clicking on the Start button on the session window. This will send a call to the peer station, and wait for a response. If the peer station is listening and ready, it will answer your call, and the session will begin. You will see the status and progress of the session on the session window and the virtual TNC window. You will also hear the sound of the data transmission on your radio speaker or headphones.
- Send and receive messages by clicking on the Send/Receive Messages button on the session window. This will transfer the messages in your outbox and inbox between you and the peer station. You can also monitor the messages on the session window and the virtual TNC window. You will see the message size, priority, and status, as well as the transmission speed and quality.
- End the peer-to-peer connection by clicking on the Stop button on the session window. This will send a disconnect signal to the peer station, and terminate the session. You will see the session summary and statistics on the session window and the virtual TNC window. You will also hear the sound of the data transmission on your radio speaker or headphones.

## How to receive peer-to-peer connectivity?
To receive peer-to-peer connectivity, you will need to follow these steps:

- Launch Winlink Express or Airmail and enter your callsign and password. If you do not have a password, leave it blank and one will be assigned to you after your first connection. You can also enter your grid square and recovery email address for your account settings.
- Choose the mode of operation from the drop-down menu on the top left corner of the window. For this article, I will use Winmor Winlink, which is a data mode for HF radio. You can also choose other modes, such as Packet Winlink, Pactor Winlink, or Vara Winlink, depending on your equipment and preference.
- Open a session by clicking on the Open Session button on the top right corner of the window. This will open a new window where you can see the status and progress of your connection. You will also see an icon down in the taskbar for your virtual TNC software, such as SoundModem, Direwolf, or Winmor TNC. Click on it (or Alt-Tab to it) and another window will open up that shows the waterfall, meter dials and transmission speed for the session once underway, along with other information.
- Tune your radio to the frequency of the peer station, and adjust your interface device and virtual TNC software settings to optimize your radio communication. You will need to set the audio levels, the modulation mode, the baud rate, the frequency correction, and other parameters according to your radio and interface device specifications. You can also use the Test and Tune function of Winlink Express or Airmail to test your radio connection and adjust your settings accordingly.
- Listen for the peer-to-peer call by clicking on the Listen button on the session window. This will put your station in a listening mode, and wait for a call from the peer station. If the peer station initiates a call, you will hear the sound of the data transmission on your radio speaker or headphones, and see the status and progress of the connection on the session window and the virtual TNC window.

You have reached the end of this series of articles. I may add more articles in this series at a later date, but that's all for now!

