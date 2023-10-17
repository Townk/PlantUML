# PlantUML Themes

This repository is my personal library of PlantUML themes.

## Usage

``` text
!theme elegant from https://raw.githubusercontent.com/Townk/PlantUML/master/themes
```

Once you add this line to your PlantUML diagram, you can use some helper functions to define extra content on your diagram:

- `$set_title(text)` :: as the name implies, define the title of your diagram;
- `$set_legend(color1,name1,color2,name2,...)` :: define a colored legend for your diagram;

If you want to add a copyright header and footer, you can set the `COPYRIGHT_OWNER` **before** setting the theme, for instance:

``` puml
@startuml
!COPYRIGHT_OWNER = "Amazon.com"

!theme elegant from https://raw.githubusercontent.com/Townk/PlantUML/master/themes

' Start your diagram here

@enduml
```

If the PlantUML version you have available is before `1.2021.6`, you can still use the themes in this repository with the pre-processor `!include`, for instance:

``` puml
@startuml
!COPYRIGHT_OWNER = "Amazon.com"

!include https://raw.githubusercontent.com/Townk/PlantUML/master/themes/puml-theme-elegant-light.puml

' Start your diagram here

@enduml
```

