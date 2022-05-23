<a name="top"></a>
# 🚀 Recipes React components

This list contains all the components created during the development of the Recipes application, which has web and mobile versions. These components were structured to facilitate their re-implementation as the marketplace progresses.

![]()
 
## Índice de contenidos
[Frontend](#item0)
* [AppLayout](#item1)
	 * [NavBar](#item2)
	 * [NavInfo](#item3)
	 * [Footer](#item4)
* [LoginForm](#item5)
* [RegisterForm](#item6)
* [SwiperHome](#item7)
* [Card](#item8)
* [CategorySectionCard](#item9)
* [PopularSearch](#item10)
* [WeightPlan](#item11)
* [CategoriesVideo](#item12)
	* [SesionCategory](#item13)
	* [VideoCategory](#item14)
	* [Video](#item15)
* [Recipes](#item16)
* [ChefsCountries](#item17)
* [AuthModal](#item18)
* [ButtonSupr](#item19)
* [MenuLeft](#item20)
* [CategoriesRecipes](#item21)
* [SelectCategory](#item22)
* [SelectRank](#item23)
* [ButtonRank](#item24)
* [BannerChef](#item25)
* [ButtomButton](#item26)
* [ProductImagenCarousel](#item27)
* [Matches](#item28)
* [MenuConfig](#item29)
* [MyAccountLayout](#item30)
* [PageLogo](#item31)
* [NavSearchBar](#item32)
* [CertificationChef](#item33)
* [Post](#item34)
* [DescriptionChef](#item35)
* [ButtonImage](#item36)
* [Details](#item37)
* [ButtonComprar](#item38)
* [Tab](#item39)
* [TabButton](#item40)
* [TabPanel](#item41)
* [TabsContainer](#item42)
* [TotalShopping](#item43)
* [TotalShoppingPrice](#item44)
* [InformationChef](#item45)
* [DescriptionPost](#item46)
* [CalendarDay](#item47)
* [calendar](#item48)
* [RequireAuth](#item49)
* [ScrollNavegacion](#item50)
* [SearchHome](#item51)
* [ButtonSearch](#item52)
* [WeightPlan](#item53)
* [Swiper](#item54)
* [config](#item55)
* [DescriptionChef](#item56)
* [DescriptionPost](#item57)
* [FormAccount](#item58)
* [InformacionChef](#item59)
* [ingredientRow](#item60)
* [ingredientRowDetails](#item61)
* [LyOverview](#item62)
* [MealDetailOverview](#item63)
* [MealDetailOverviewImages](#item64)
* [PasswordUser](#item65)
* [PaypalLogin](#item66)
* [PaypalUser](#item67)
* [ProductInfo](#item68)
* [BannerPage](#item69)
* [BoxCalendar](#item70)
* [BoxName](#item71)
* [ButtonCart](#item72)
* [ButtonChange](#item73)
* [ButtonItems](#item74)
* [SelectOrder](#item75)
* [CardChef](#item76)
* [CardGym](#item77)
* [CardOrder](#item78)
* [CardPaypal](#item79)
* [CardProduct](#item80)
* [Card Recipes](#item81)
* [CardResum](#item82)
* [CardWithTitle](#item83)
* [Checkbox](#item84)
* [CheckboxConfig](#item85)
* [WaPay](#item86)

 
<a name="item0"></a>
## [Frontend](https://github.com/RecipesApp2022/RecipesReactComponents-Frontend/blob/main/README.md "Frontend") 🚀
 


 
<a name="item1"></a>
### AppLayout
 
AppLayout es un componente padre de enrutamiento entre los hijos NavBar, NavInfo y Footer. Este contiene una variable que permite agregar el contenido correspondiente a cada página de la aplicación. 

 
[Subir](#top)


 
<a name="item2"></a>
* ### NavBar
 
Contiene la parte superior del header donde se ubican los items que direccionan la navegación del usuario hacia categorías, vendedores e inicio de sesión.  

 
[Subir](#top)



 
<a name="item3"></a>
* ### NavInfo
 
Contiene la barra inferior del header, está compuesto por la localización, direccionamientos hacia recetas, planes y combos. 

 
[Subir](#top)




 
<a name="item4"></a>
* ### Footer
 
Almacena toda la información del pié de página.
 
[Subir](#top)




<a name="item5"></a>
### LoginForm
 
Vista del login donde el usuario agrega datos para validar su acceso a la plataforma.

 
[Subir](#top)


<a name="item6"></a>
### RegisterForm
 
Página en la cual el usuario puede rellenar los campos requeridos para el registro en la aplicación. 
 
[Subir](#top)




<a name="item7"></a>
### SwiperHome
 
Contiene las imágenes de portada modo slider. 
 
[Subir](#top)



<a name="item8"></a>
### Card
 
Titulación de las secciones. Recibe parámetro de texto modificable, debido a que se utiliza en varias secciones del home.

 
[Subir](#top)



<a name="item9"></a>
### CategorySectionCard
 
Componente utilizado para las imágenes de las categorías.

[Subir](#top)




<a name="item10"></a>
### PopularSearch
 
Rectángulo con estilos específicos donde se agrega la información, imagen y texto de una sección publicitaria. 
 
[Subir](#top)



<a name="item11"></a>
### WeightPlan
 
Sección de los planes, donde se trae información de los planes como imagen, título y descripción breve. 
 
[Subir](#top)


<a name="item12"></a>
### CategoriesVideo
 
Toda la sección de categorías con videos. 
 
[Subir](#top)



<a name="item13"></a>
* ### SesionCategory
 
Select de las categorías.

[Subir](#top)


<a name="item14"></a>
* ### VideoCategory
 
Descripción del video, contiene imagen y nombre del vendedor, nombre de la receta. 
 
[Subir](#top)




<a name="item15"></a>
* ### Video
 
Modelo de la estructura de la card donde se muestra el video.
 
[Subir](#top)



<a name="item16"></a>
### Recipes
 
Componente que contiene la estructura de la plantilla de como se muestra la receta en el home. 
 
[Subir](#top)



<a name="item17"></a>
### ChefsCountries
 
Contiene sección de chefs populares por países. 
 
[Subir](#top)


<a name="item18"></a>
### AuthModal
 
Este componente es el encargado de la validación de escuchar el clic al seleccionar el Button de inicio de sesión donde nos permite iniciar en la vista del login o en la vista del registro.

 
[Subir](#top)



<a name="item19"></a>
### ButtonSupr
 
Componente con las dos opciones de vista (Grid View, ListView). en las pantallas de resultados de busqueda.

 
[Subir](#top)



<a name="item20"></a>
### MenuLeft

Este componente es el encargado de la estructura del sistema de filtrado que aparece en el lateral izquierdo en las pantallas de resultados de búsqueda.  A su vez contiene 6 componentes.   

 
[Subir](#top)



<a name="item21"></a>
### CategoriesRecipes
 
Componente encargado del filtrado por categorías.

 
[Subir](#top)



<a name="item22"></a>
### SelectCategory
 
Componente encargado del filtrado por Types.

 
[Subir](#top)



<a name="item23"></a>
### SelectRank
 
Componente encargado del filtrado por Ranking. 

 
[Subir](#top)



<a name="item24"></a>
### ButtonRank 
 
Componente con botones para aplicar o resetear los filtros.

 
[Subir](#top)



<a name="item25"></a>
### BannerChef
 
Este componente contiene la estructura de las cards con la información mostrada de cada vendedor desde la vitrina de vendedores y el home.

 
[Subir](#top)



<a name="item26"></a>
### ButtomButton
 
Componente con botones de paginación que se repite en varias secciones.

 
[Subir](#top)






<a name="item27"></a>
### ProductImagenCarousel

Componentes con la vista de las imagenes en el detalle del producto

 
[Subir](#top)







<a name="item28"></a>
### Matches
 
Botones de interaccion con funcionalidades para hacer match, agregar a favoritos o descartar un producto.

 
[Subir](#top)



<a name="item29"></a>
### MenuConfig
 
Componente padre del menu desplegable del panel de usuario con iconos e item.

 
[Subir](#top)



<a name="item30"></a>
### MyAccountLayout
 
Panel de herramientas del usuario vista con iconos.

 
[Subir](#top)




<a name="item31"></a>
### PageLogo
 
Componente con el logo de la app que se adapta al tamaño adecuado.

 
[Subir](#top)





<a name="item32"></a>
### NavSearchBar
 
Select de los tipos que encontramos en el header.

 
[Subir](#top)




<a name="item33"></a>
### CertificationChef
 
Componente con informacion profesional del vendedor desde su perfil.

 
[Subir](#top)






<a name="item34"></a>
### Post
 
Entradas del blog del vendedor ubicadas en el lateral izquierdo del perfil del vendedor.

 
[Subir](#top)






<a name="item35"></a>
### DescriptionChef
 
Descripcion escrita por el vendedor en su perfil

 
[Subir](#top)





<a name="item36"></a>
### ButtonImage
 
Este componente contiene los botones de opcion de compra de ingredientes en Wallmart, Insta card y Amazon Fresh, los cuales redireccionan hacia estos sitios para realizar la compra con esos supermercados. Asi mismo se encuentra dentro de este el boton de pago del producto (receta, plan o combo) a traves de pay pal. 

 
[Subir](#top)





<a name="item37"></a>
### Details
 
components que encargado de mostrar esta informacion que se encuentra en la vista de detalle de recetas, combos y planes (Level, categoria, time, igredientes)

 
[Subir](#top)






<a name="item38"></a>
### ButtonComprar
 
Componentes de boton de comprar (desde la caja blanca hasta el boton en la vista del detalle del producto(recetas....) 

 
[Subir](#top)





<a name="item39"></a>
### Tab
 
Componente dinamico encargado del movimiento del cambio de las lista seleccionada.

 
[Subir](#top)







<a name="item40"></a>
### TabButton
 
componente creado del diseño de dos botones stores y the best offer (ya no se utiliza pero esta alli por si se llega a necesitar)

 
[Subir](#top)





<a name="item41"></a>
### TabPanel
 
componente encargado de mostar o ocultar la informacion de sus hijos dependiendo de la pestaña seleccionada.

 
[Subir](#top)







<a name="item42"></a>
### TabsContainer
 
chequea que sus hijos si es 1 lo muestra si son muchos lo rederiza.

 
[Subir](#top)





<a name="item43"></a>
### TotalShopping
 
componente encargado de mostrar imagen de un tamaño en particular para la vista del producto
 
[Subir](#top)







<a name="item44"></a>
### TotalShoppingPrice
 
Componente  encargado de mostrar precio en la vista del detalle del producto unico

 
[Subir](#top)





<a name="item45"></a>
### InformationChef
 
componente encargado de Mostrar las redes sociales de chef

 
[Subir](#top)







<a name="item46"></a>
### DescriptionPost
 
Componente encargado de mostra del detalle de la descripcion de post del blog

 
[Subir](#top)





<a name="item47"></a>
### CalendarDay
 
Componente encargado de recibir el dia correspondiente del calendar

 
[Subir](#top)








<a name="item48"></a>
### calendar
 
Componente encargado del diseño del calendario 

 
[Subir](#top)




<a name="item49"></a>
### RequireAuth
 
Componente de autenticacion del login de usuario. Envuelve MyAccountLayout.

 
[Subir](#top)






<a name="item50"></a>
### ScrollNavegacion
 
Componente encargado de contener el diseño circular. componente principal ButtonButton(ScrollNavegacion)

 
[Subir](#top)





<a name="item51"></a>
### SearchHome
 
Componente encargado de motor de Busqueda en el home contiene el componente ButtonSearch

 
[Subir](#top)



<a name="item52"></a>
* ### ButtonSearch
 
Componente encargado del selector de busqueda por sus categorias.

 
[Subir](#top)





<a name="item53"></a>
### WeightPlan
 
Componente de la vista de cuadro de planes. 
 
[Subir](#top)







<a name="item54"></a>
### Swiper
 
CategoryCard, Combos, Home, Overview, Popular, Recipes, WeightPlan

 
[Subir](#top)





<a name="item55"></a>
### config
 
Componente de la parte del usuario en la vista de configuracion 

 
[Subir](#top)





<a name="item56"></a>
### DescriptionChef
 
Componente encargado del chef de la description del menu lateral

 
[Subir](#top)





<a name="item57"></a>
### DescriptionPost
 
Componente encargado de mostrar la informacion de post de Anya del menu lateral
 
[Subir](#top)








<a name="item58"></a>
### FormAccount
 
Componente de la iformacion personal de user en la vista de usuario (my personal informayion)

 
[Subir](#top)





<a name="item59"></a>
### InformacionChef
 
Datos de la redes sociales del cheft que aparece en el menu lateral

 
[Subir](#top)







<a name="item60"></a>
### ingredientRow
 
Componente encargado del diseño del cuadro de la lista de ingredientes.

 
[Subir](#top)





<a name="item61"></a>
### ingredientRowDetails

Componente encargado del detalle que lleva cada vista de la lista de ingrediente

 
[Subir](#top)




<a name="item62"></a>
### LyOverview

Componente encargado del siseño de las letras de la vista overview
 
[Subir](#top)




<a name="item63"></a>
### MealDetailOverview

componente del scroll de la vista por dia.

 
[Subir](#top)




<a name="item64"></a>
### MealDetailOverviewImages

Componete encargado de mostrar la imagenes al seleccionar un cuadro de la vista de overview.
 
[Subir](#top)




<a name="item65"></a>
### PasswordUser

Componente donde permite al usuario agregar contraseña en la vista paypal user

 
[Subir](#top)




<a name="item66"></a>
### PaypalLogin

Componente  creado para la vista de login de paypal (no se usara) 
 
[Subir](#top)




<a name="item67"></a>
### PaypalUser

Componente donde se encarga de colocar la informacion de my paypal en la vista de user.
 
[Subir](#top)




<a name="item68"></a>
### ProductInfo

Componente que se encarga mnostar todo el contenido de la vista de detalle del producto.
 
[Subir](#top)




<a name="item69"></a>
### BannerPage

componente del banner de las diferente vista (revision).
 
[Subir](#top)




<a name="item70"></a>
### BoxCalendar

Componente encargado del diseño del cuadro del calendario de la vista del usuario
 
[Subir](#top)




<a name="item71"></a>
### BoxName

componente que recibe el texto del diade la semana (Sunday, Monday, Tuesday, Wednesday, Thursday, Friday).
 
[Subir](#top)




<a name="item72"></a>
### ButtonCart

Componente del boton de carrito
 
[Subir](#top)




<a name="item73"></a>
### ButtonChange

Componente del boton de change
 
[Subir](#top)




<a name="item74"></a>
### ButtonItems

Componente que se encarga del siseño del boton de seleccion de (recipes, plans y combos?
 
[Subir](#top)




<a name="item75"></a>
### SelectOrder

Componente del diseño de lista de ordenar por del vendedor.	
 
[Subir](#top)




<a name="item76"></a>
### CardChef

Componente del vendedor. Vista sellers.
 
[Subir](#top)




<a name="item77"></a>
### CardGym

Componente repetido mejorar.
 
[Subir](#top)




<a name="item78"></a>
### CardOrder

Componente donde aparece foto de nombre del vendedor, order, sellers.
 
[Subir](#top)




<a name="item79"></a>
### CardPaypal

Componente que se encuentra en la vista de la forma de pago de paypal (logo y modificar).
 
[Subir](#top)




<a name="item80"></a>
### CardProduct

Componente que contiene imagen y tirulo del producto en al vista de paypal.
 
[Subir](#top)




<a name="item81"></a>
### CardRecipes

Componente de las recetas. 
 
[Subir](#top)




<a name="item82"></a>
### CardResum

Componente de orden de resum en paypal.
 
[Subir](#top)




<a name="item83"></a>
### CardWithTitle

Componente que fue realizado para la parte de configuraciones de My servings en la vista de usuario.
 
[Subir](#top)






<a name="item84"></a>
### Checkbox

Componente del checkbok cuadrado.
 
[Subir](#top)




<a name="item85"></a>
### CheckboxConfig

Componente del checkbok circular.
 
[Subir](#top)




<a name="item86"></a>
### WaPay

Componente encargado de mostrar la informacion de la lista de comparador de precio
 
[Subir](#top)


