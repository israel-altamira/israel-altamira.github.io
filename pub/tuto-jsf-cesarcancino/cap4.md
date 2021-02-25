
## VideoTutorial 4 del Taller Práctico de Java Server Faces. Reglas de Navegación.

1. Invoke template through welcome file tag
2. Implicit Navigation 
   - ```<h:commandLink value="" action="inicio">``` 
      - translated to an anchor \<a\>
      - plus JS \<script\> + \<a\> anchor + form post action to same address
   - ```<h:commandButton value="" action="inicio">``` 
      - translated to a \<input\> type submit + form post action to same address
   - ```<h:link value="" outcome="inicio">``` 
      - translated to an anchor \<a\>
      - direct link to inicio.xhtml
3. Dynamic Navigation
   - ```<h:commandLink value="" action="page1">``` 
      - translated to an anchor \<a\>
      - plus JS \<script\> + \<a\> anchor + form post action to page1.xhtml
   - ```<h:commandLink value="" action="#{bean.method()}">```
      - configuration in faces-config.xml for navigation rules
      - configuration in faces-config.xml for managed bean



<img src="./4%2001.png" width="" /> <hr/>
<img src="./4%2002%2001.png" width="" /> <hr/>
<img src="./4%2002%2002.png" width="" /> <hr/>
<img src="./4%2003%2001.png" width="" /> <hr/>
<img src="./4%2003%2002.png" width="" /> <hr/>
<img src="./4%2004%2001.png" width="" /> <hr/>
<img src="./4%2004%2002.png" width="" /> <hr/>
<img src="./4%2005%2001.png" width="" /> <hr/>
<img src="./4%2005%2002.png" width="" /> <hr/>
<img src="./4%2006%2001.png" width="" /> <hr/>
<img src="./4%2006%2002.png" width="" /> <hr/>
<img src="./4%2006%2003.png" width="" /> <hr/>
<img src="./4%2006%2004.png" width="" /> <hr/>
<img src="./4%2006%2005.png" width="" />

