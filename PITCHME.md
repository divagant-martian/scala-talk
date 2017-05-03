![LOGO](https://github.com/zombiefungus/scala-talk/raw/master/assets/images/scala-logo.png)

Programación Orientada a Objetos

<span class="red">+</span>

Programación Funcional

---

##¿Por qué crear Scala?

---


####<span class="dgray">Idea</span>
###<span class="orange">Mejorar</span> Java
###sin <span class="orange">conflictuar</span> con este

---
####<span class="dgray">Cómo</span>
###Abordando <span class="orange">críticas</span> a Java
###Manteniendo <span class="orange">interoperabilidad</span>

<span class="paren">[ Java Bitecode -> JVM ]</span>

<span class="paren">[ Uso de librerías sin distinción ]</span>

---
####Lo mejor de dos mundos
### <span class="orange">Objetos</span>

<span class="paren">[ Reutilización de código, Encapsulamiento, ... ]</span>

### <span class="orange">Funcional</span>

<span class="paren">[ Inmutabilidad, Mónadas, Inferencia de tipos, Pattern matching, ... ]</span>

---
#### <span class="red">¿Quién lo usa?</span>

<img src="https://cdn4.iconfinder.com/data/icons/social-messaging-ui-color-shapes-2-free/128/social-linkedin-square2-128.png"
     alt="LinkedIn" height="100">
<img src="https://edubloxtutor.com/wp-content/uploads/2016/11/twitter-3-xxl.png"
     alt="Twitter" height="100">
<img src="https://www.shareicon.net/data/128x128/2016/07/16/796802_logo_512x512.png"
     alt="Foursquare" height="100">
<img src="https://img.clipartfest.com/41febf049d705f818380e1f03ed4e091_free-icons-clipart-netflix_256-256.png"
     alt="Netflix" height="100">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/Tumblr.svg/256px-Tumblr.svg.png"
     alt="Tumblr" height="100">
<img src="http://riga.esn.lv/sites/default/files/partners/images/airbnb.png"
     alt="AirBnB" height="100">
<img src="http://icons.iconarchive.com/icons/danleech/simple/256/meetup-icon.png"
     alt="Meetup" height="100">
<img src="http://www.omavahti.fi/wp-content/uploads/2015/02/sony-logo-slogan.png" alt="Sony" height="100">

+++

---
#### <span class="red">Herramientas en Scala</span>

<img src="https://svbtleusercontent.com/ivdemz9z9lsm6g_small.png"
     alt="Spark" height="100">
<img src="https://svn.apache.org/repos/asf/kafka/site/logos/originals/png/WIDE%20-%20Black%20on%20Transparent.png"
     alt="Kafka" height="100">

<img src="https://upload.wikimedia.org/wikipedia/commons/5/50/Samza_Logo.png"
     alt="Samza" height="100">
<img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/5e/Akka_toolkit_logo.svg/1280px-Akka_toolkit_logo.svg.png"
     alt="Akka" height="100">

+++

---

###Hola Mundo

<span class="red">Compilado</span>
```scala
object HelloWorld extends App {
println("Hello, World!")
}
```
<span class="red">Interpretado</span>
```scala
println("Hello, World!")
```

---
##Features

---
###Fuerte sistema de tipado estático

Un ejemplo en <span class="dgray">Python</span>

```python
def foo(x):
    return x*3
```

Qué tipo de dato recibe?

Qué tipo de dato retorna?

---

- <span class="paren">`foo(4) == 12`</span>
- <span class="paren">`foo("what?!") == "what?!what?!what?!"`</span>
- <span class="paren">`foo(True) == 3`</span>
- <span class="paren">`foo(False) == 0`</span>
- <span class="paren">`foo({'one':'uno'})` -> `unsupported operand type(s) for *: 'dict' and 'int'`</span>

---

###Inferencia de tipos

Esto es obvio

```java
int num = 14;
```

Esto también

```
String str = "DAHH, soy un String!!"
```

Esto requiere más esfuerzo

```java
private int tres() { return 3; }
...
int mi3 = tres();
```

Pero es posible

---
###Tipos de datos inmutables

---
###Evaluación peresoza

---
###Programación de alto orden

---
###Sobrecarga de operadores

---
<span style="color: #e49436">STEP 2. GIT-COMMIT</span>

![TERMINAL](https://d1z75bzl1vljy2.cloudfront.net/hello-world/terminal.png)

Git-commit on any branch and push your PITCHME.md to GitHub, GitLab or Bitbucket.

---

<span style="color: #e49436">STEP 3. GET THE WORD OUT!</span>

<br>

<span style="font-size: 1.3em;"><span style="color:white">htt</span><span style="color:white">ps://git</span><span style="color: #e49436">pitch</span><span style="color: white">.com/<span style="color: #e49436">user</span>/<span style="color: #e49436">repo</span>/<span style="color: #e49436">branch</span></span>

<br>

Instantly use your GitPitch slideshow URL to promote, pitch or present absolutely anything.

---

<span style="color: #e49436">GIT</span>PITCH DESIGNED FOR SHARING

![SOCIAL](https://d1z75bzl1vljy2.cloudfront.net/hello-world/gp-social.jpg)

- View any slideshow at its public URL
- Promote any slideshow using a GitHub badge
- Embed any slideshow within a blog or website
- Share any slideshow on Twitter, LinkedIn, etc
- Print any slideshow as a PDF document
- Download and present any slideshow offline

---

<span style="color: #e49436">GIT</span>PITCH FEATURE RICH SLIDESHOWS

- GitHub Flavored Markdown +
- Code Block and GIST Slides
- Image and Video Slides
- Custom Logos and Backgrounds
- Multiple Themes And More
- <span style="color: #e49436">Plus...</span>
- Your Slideshow Is Part Of Your Project
- Under Git Version Control Within Your Git Repo


---

### Go for it.
### Just add <span style="color: #e49436; text-transform: none">PITCHME.md</span> ;)

```

```
