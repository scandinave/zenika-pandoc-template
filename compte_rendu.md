---
title: Zenika Template
author: Your Name
date: Janvier 2023
logo: images/logo_light
logo_footer: images/logo_footer
figure_placement: H
toc: true
start_with_new_page: true
--- 

# Titre 1

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui.

## Titre 2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui.

### Titre 3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui.

#### Titre 4

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui.

##### Titre 5

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui.

##### Titre 6

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui.


## Formatage du texte
### Texte  en italique
_Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ac interdum massa, accumsan dictum dui. Cras sollicitudin 
non leo eget tristique. Praesent vel consequat eros. Nunc elit justo, tincidunt at nibh ut, molestie blandit sapien. 
Duis leo dolor, aliquet vel neque pulvinar, rutrum vehicula ex. Vivamus facilisis ligula elementum, rutrum libero vitae,
pulvinar tortor. Fusce iaculis malesuada est eu viverra._ 

### Texte en gras
*Interdum et malesuada fames ac ante ipsum primis in faucibus. Donec varius felis et dui laoreet pellentesque. 
Nulla accumsan elit ullamcorper convallis placerat. Quisque sit amet vulputate arcu. Phasellus commodo id neque non 
fermentum. Aliquam molestie risus lacus, sit amet efficitur ipsum feugiat at. Ut vestibulum semper porttitor. Morbi 
condimentum consectetur dui. Sed aliquet lacus ut diam commodo pellentesque quis sit amet ligula. Integer quis arcu sed 
urna scelerisque tempus. Suspendisse potenti. Donec euismod aliquet lorem, et pretium libero congue sit amet. Quisque 
tempus semper mauris ac ornare. Proin suscipit est sit amet felis euismod rhoncus. Duis massa mauris, congue vel eros 
vitae, maximus imperdiet sapien. Sed pretium metus a sodales facilisis.*


### Liste à puce

* Interdum et malesuada fames ac ante ipsum primis in faucibus
* Sed pretium metus a sodales facilisis
* Sed aliquet lacus ut diam commodo pellentesque quis sit amet ligula

1. Interdum et malesuada fames ac ante ipsum primis in faucibus
2. Sed pretium metus a sodales facilisis
3. Sed aliquet lacus ut diam commodo pellentesque quis sit amet ligula

\newpage

## Infobulle

```{=latex}
\notebox{
 Infobulle info
}
```

```{=latex}
\tipbox{
 Infobulle astuce
}
```

```{=latex}
\warningbox{
Infobulle Attention
}
```

```{=latex}
\cautionbox{
Infobulle Danger
}
```

```{=latex}
\notebox{
InfoBull avec liste à puce
\begin{itemize}
    \item Attribute-based access control (ABAC),
    \item Role-based access control (RBAC),
    \item User-based access control (UBAC),
    \item Context-based access control (CBAC),
    \item Rule-based access control using JavaScript, 
    \item Time-based access control,
    \item Support for custom access control mechanisms (ACMs) through a Service Provider Interface (SPI),
\end{itemize}
}
```

## Saut de page 

```latex
\newpage
```

\newpage

## Code

```json
{
  "exp": 1674723026,
  "iat": 1674719426,
  "iss": "https://sso.gorenove.fr/auth/realms/gorenove-particulier-prod"
}
```


