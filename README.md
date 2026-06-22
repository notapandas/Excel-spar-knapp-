# Excel-spar-knapp-

instruktioner för att installera 

Öppna VBA funktion + 11

insert user form 
frmSaveExport

UI build
label 1 
Save workbook & PDF

Font Size: 16
Font Bold: True

label 2

File Name

label 3

Save Location

Textbox 1

name:
txtFileName

textbox 2

name:
txtFolder

locked:
True

Knappar

Browse

name:
btnBrowse

caption:
Browse...

Save knapp

name:
btnSave

caption:
Save Files

cancel button

name:
btnCancel

caption:
Cancel


Form Background
BackColor: White
Width: 420
Height: 240

styling
SpecialEffect: fmSpecialEffectFlat


lägg till macro

Insert → Module

Sub OpenSavePopup()

    frmSaveExport.Show

End Sub

lägg till excel 

Excel → Preferences → Ribbon & Toolbar

slå på developer

lägg till knapp

Developer → Insert → Button

lägg till macro
OpenSavePopup

namn 
export knapp
