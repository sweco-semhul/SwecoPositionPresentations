SwecoPositionPresentations
==========================


För att lägga till en presentation koperia in embedd urlen i arrayen **presentations**

```
var presentations = [
	{
		name: '{{name of presentation}}',
    	time: {{time in second}},
    	url: '{{url to presentation}}'
	}
]
```

### PowerPoint (Microsoft Office 365 (OneDrive aka SkyDrive))
Glöm inte se till att din PowerPoint har automatisk frammatning aktiverad.

1. Gå till http://www.office365.com, klicka Sign in och logga in.
2. Klicka på SkyDrive (eller OneDrive som den snart kommer heta) uppe till höger i menyn
3. Klicka på *New document*
4. Välj *ladda upp befintlig fil*
5. Öppna den presentationen, genom att klicka på den i listan
6. Välj *File/Arkiv* i menyn 
7. Välj *Share/Dela*
8. Klicka på *Share with People*
9. Klicka på *Get a link*
10. Klicka på *CREATE LINK*
16. Kopiera URL:en och klistra in det enligt konfigurationen ovan

### Google Drive
1. Öpnna presentationen i Google Drive
2. Välj *File*
3. Välj *Publish to the web*
4. Välj en tid för övergångar mellan bilder under *Automatically advance presentation to the next slide*
5. Klicka i *Start slideshow as soon as the player loads* och *Restart slideshow after the last slide*
6. Kopiera URL:en ur src="" attributet och klistra in det enligt konfigurationen ovan

### slid.es
1. Klicka på *Visibility-ikonen*
2. Välj *Public*
3. Klicka på *Share-ikonen*
4. Välj Footer style i drop-downen
5. Kopiera URL:en ur src="" attributet och klistra in det enligt konfigurationen ovan

