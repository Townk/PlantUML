# PlantUML Themes

This repository is my personal library of PlantUML themes.

## Usage

``` text
!theme elegant from https://raw.githubusercontent.com/Townk/plantumllib/master/themes
```

Once you add this line to your PlantUML diagram, you can use some helper functions to define extra content on your diagram:

- `$set_title(text)` :: as the name implies, define the title of your diagram;
- `$set_legend(color1,name1,color2,name2,...)` :: define a colored legend for your diagram;

If you want to add a copyright header and footer, you can set the `COPYRIGHT_OWNER` **before** setting the theme, for instance:

``` puml
@startuml
!COPYRIGHT_OWNER = "Amazon.com"

!theme elegant from /Users/thiagoa/workplace/personal/plantuml/plantumllib/themes/elegant

' Start your diagram here

@enduml
```

