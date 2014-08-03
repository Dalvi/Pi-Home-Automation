Pi-Home-Automation
==================

Complete Home Automation done with Raspberry Pi as central brain

  
**Project goals**
  
Basic
- Start/Stop appliances (lights, hvac (ac, central heating), power-plugs in general)
- Dim and preset normal and RGB LED lighting
- Record patterns on above and play it back (deterring thieves), create random patterns
- Manual scheduling the above
- Web interface 
- Strong security, user roles (admin, operators, read-only guests)
- API for plugins
- Self diagnostics 
- Auto-update (optional)
  

Extras (mostly done by plugins)
- DVR and action triggers on cam events (night, movement - like lighting the pathway of someone going through the house)
- alarms (left alone cat didn't move all day, too much noise in the house, flooding, someone is taking your car)
- voice commands
- call predefined number (requires GSM module or using a service)
- call emergency numbers with automatically generated voice reports
- personal assistant (Google Now like)
  
Security is very important, a lot of work will be done to prevent unauthorized/malicious action
  
*Contributors are welcome!*
  
Scenarios:  
**I**
You wake up, get out of bed, and you have to go to work. 
- It's still dark (winter season). Lights turn on on your path.
- Radio is starting, coffee is done or getting done.
- "- No incident last night, it seems you slept well" you hear.
- "- It's sunny outside, but there is a chance of rain in the afternoon. Temp will be xx degrees"
- You ask for the agenda for the day, work or otherwise.
- You dress and prepare to take off.
- "- Where are my keys?" you ask. "- You left them on the kitchen table"
- You leave
- 1 minute after, lights and central heating is turned off, perimeter alarm is armed
  

**II**
Intruder breaks in. 
- You're notified and upon viewing a report with a picture, you approve calling emergency number (neighbour even).
- You can speak to the intruder if you want to, maybe to persuade them to abort the theft
