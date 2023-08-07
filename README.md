<h1>Hi👋, I'm Ajmal Bin Nizam! <img src="https://media.giphy.com/media/xTiTnnnWvRXTeXx3wc/giphy.gif" width="50"></h1>

<img src="contributions.svg">

<h2 style="margin:10;">Working as a Full stack Data engineer in <a href="https://www.ey.com">EY GDS</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</h>

<h3 style="margin-top:20px;">🔥Current Technologies: </b></h3>
<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
<a href="https:https://www.databricks.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/databricks/databricks-icon.svg" alt="databricks" width="40" height="40"/> </a> 
<a href="https://azure.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Microsoft_Azure.svg" alt="azure" width="40" height="40"/> </a> 
<a href="https://powerbi.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="powerbi" width="40" height="40"/> </a> 
<a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> 
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> 
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/selenium.svg" alt="git" width="40" height="40"/> </a> 
</p>

<h3 style="margin-top:20px;">❄️ Depreciated Technologies </b></h3>
<p align="left">
<a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Microsoft_.NET_logo.svg/2048px-Microsoft_.NET_logo.svg.png" alt="csharp" width="40" height="40" style="margin-left:7px;"/> </a>  
<a href="https://www.angular.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/angular/angular-icon.svg" alt="angular" width="40" height="40"/> </a> 
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>  </p>

## Connect with me:

<a href="https://instagram.com/ajmalbinnizam"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Instagram_colored_svg_1-512.png" width="26"> </a>
<a href="https://www.linkedin.com/in/ajmalbinnizam/"><img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" width="30"> </a>
<a href="https://ajmalbinnizam.github.io"><img src="https://img.icons8.com/fluent/96/000000/domain.png" width="30" alt="ajmal bin nizam"/></a>
<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">


```python
class DataEngineer:
    def __init__(self):
        self.name = "ajmal bin nizam"
        self.role = "Data Engineer in EY GDS"
        self.location = "8.8932\xc2\xb0 N, 76.6141\xc2\xb0 E"
        self.blog = "https://ajmalbinnizam.medium.com/"
        self.knowledge_base = ["Data Engineering", "Machine Learning", "music production"]
        self.knowledge_base.insert(0, "data and analytics")
    def say_hi(self):
        print(
            """Hello my friend, thanks for dropping by!
This is {name}, living in {location}. I work as an {role}.
Currently focusing on things that excits me such as {knowledge_base}
Whenever inspiration strikes, I scribble down something here: {blog} 
""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                knowledge_base=", ".join(self.knowledge_base[1:]),
                blog=self.blog,))
                
me = DataEngineer()
me.say_hi()
```

<a href="https://shorturl.at/flY36">Click here, to run the code</a>
