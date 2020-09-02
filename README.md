# goit-markup-hw-08

<batom>Все</batom>
<batom>Веб-сайты</batom>
<batom>Приложения</batom>
<batom>Дизайн</batom>
<batom>Маркетинг</batom>

Raleway Bold
Roboto Medium
Roboto Regular
Roboto Bold
Roboto Black

<!--виписуємо класи по секціях--> 

<!--Загальні класи для всіх-->
link 
active
list
button 
text
second-title
img 

<!--navigation-->
navigation 
header-logo 
logo-web 
navigation-list 
navigation-list-item 
navigation-line-studio ? для псевдокласу after 
navigation-list-link 
<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->  
.navigation-line-studio::after

address-util 
address
address-list
address-item
address-emaile
address-emaile-svg 
address-item
address-tel
address-tel-svg 



<!--заголовок і кнопка-->
decorative-img 
container-h1
maine-taitle
text-butto

<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->   




<!--Наші Стандарти-->
standards 
list-standards
standards-list-item
standards-br-svg 
standards-list-item-svg
satandards-items
text
<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->   



<!--Чем мы занимаемся--> 
projects 
second-title 
effect-studio-list-img
list-img
studio-effect-text-div
img
projects-satandards-items 
studio-effect-text

<!--Наша команда--> 
our-team-section 
our-team 
second-title
our-team-list 
manager 
our-team-list-container 
manager-name
profesion
social-list
social-list-item
solcial-link-item
solcial-icon-svg

<!--Постоянные клиенты--> 
regular-customers
second-title
regular-customers-list 
regular-customers-list-item4
regular-customers-dr
regular-customers-svg

<!--Footer: Лого, Адреса, Приєднуйтесь, Підписуйтесь--> 
<!--<div class="footer-container">--> 
footer-div-container 
footer-div-address
footer-logo logo
logo-web
list
footer-adres
address-emaile-foote
address-emaile
address-tel 
join-social-link 
action 
social-list 
vidstan-icon-footer 
social-list-item 
solcial-link-item
footer-icon-link 
solcial-icon-svg

sign-up 
action 
imput-footer
imput
footer-actions-input-text-emaile 
footter-button
olcial-icon-svg
plane-icon-send 

<!--portfolio-->
<!--Портфоліо Кнопки навігації (ВСЕ,ВЕБ_САЙТ,Додатки,Дизайн,Маркетинг)-->
div-portfolio-sectio
portfolio-button
portfolio-list-btn
portfolio-list-item-btn
button-portfolio
<!--Портфоліо Список: (ВСЕ,ВЕБ_САЙТ,Додатки,Дизайн,Маркетинг) -->
portfolio-div 
portfolio-list-works
portfolio-works-item
portfolio-focus-item 
portfolio-list-title 
portfolio-text 

effect-item-div - то ефекти !!!!
effect-div - то ефекти !!!!
text portfolio-effect-text - то ефекти !!!! 

<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->   
navigation-line-portfolio::after






<!--Модалье вікно--> 
text portfolio-effect-text

/*Модальне вікно*/
.form 
.modal-form 
.form-title 
.form-input 
.modal-form-list 
.modal-form-list:not(:last-child)
.modal-form-list:last-child 
.modal-form-list input 
}
.modal-form-list textarea 
.form-label 
.modal-form-list
.form-svg 
.form-svg 
.label-comment 
.form-label 
.input-modal 
.form-accept 
.form-mark
.form-mark-text 
.btn-form 
.btn-close 
.close-svg 
.modal-form-list:hover .form-svg 
.modal-form-list:hover input,
.modal-form-list:hover textarea 
.textarea-comment 
.modal-form-list:hover label


.form-input:focus + .form-label,
.textarea-comment:focus + .label-comment,
.form-input:not(:placeholder-shown) + .form-label,
.textarea-comment:not(:placeholder-shown) + .label-comment {
  color: #2196F3;
  top: -20px;
  left: 16px;
  box-sizing: 12px;
}
.form-input:focus ~ .form-svg {
  fill:  #2196F3;
}
.is-hidden {
  top: 200px;
  visibility: hidden;
  opacity: 0;
  pointer-events: none;
  transition: 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

<picture>
                          <source srcset="./imeges/Портфоліо/portfolio1-desk.jpg 1x, ./images/Портфоліо/portfolio1-desk@2x.jpg 2x" 
                              media="(min-width: 1200px)">
                          <source srcset="./imeges/Портфоліо/portfolio1-tab.jpg 1x, ./images/Портфоліо/portfolio1-tab@2x.jpg 2x" 
                              media="(min-width: 768px)">
                          <source srcset="./imeges/Портфоліо/portfolio1-mob.jpg 1x, ./images/Портфоліо/portfolio1-mob@2x.jpg 2x" 
                              media="(max-width: 767px)">
                          <img src="./imeges/Портфоліо/portfolio1-desk.jpg" alt="Технокряк">
                      </picture>


                       <img src="./imeges/Портфоліо/portfolio1-desk.jpg" alt="Технокряк">


                       @media screen and (min-width: 768px) {
      
/*Наші Стандарти+Чем мы занимаемся*/
.satandards-items {
  font-weight: 700;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 10px;
  color: (--title-light-theme-color);
}

.second-title {
  font-weight: 700;
  font-size: 36px;
  line-height: 1.16;
  text-align: center;
  letter-spacing: 0.03em;
  margin-bottom: 50px;
  color: $title-light-theme-color;
}
/*Декоративні ефекти + Векторна графіка*/
.standards-br-svg {
  display: inline-block;
  height: 120px;
  width: 270px;
  margin-bottom: 30px;
  background-color: $secondary-bg-color;
}
.standards-br-svg {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 354px;
  height: 120px;
  background: #f5f4fa;
  border-radius: 4px;
  padding: 25px 100px;
  margin-bottom: 30px;
}
/*наші стандарти*/

.standards {
  padding-top: 94px;
  padding-bottom: 47px;
  width: 768px;
  padding-left: 15px;
  padding-right: 15px;
  margin-left: auto;
  margin-right: auto;
}
.text {
  font-weight: 400;
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: $text-light-theme-color;
  width: 270px;
}
.list-standards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

<Section class="hawe-its-made">
      <div class="container">
      <div class="container-taitle">
        <p class="">TRADITION AND LOVE</p>
        <h2 class=""> HAW IT'S <br/> MADE?</h2>
      </div>
      <div class="container-about">
        <ul class="">
          <picture>
            <source srcset="" media="max-width: 320px" >
            <source srcset="" media="min-width: 768px" >
            <source srcset="" media="min-width: 1200px" >
          <img class="" width="280px" height="279px" src="./images/demo.jpg"  alt="фото графін зі свіжим молоком, та коровою на фоні.  Смачно як у дитинстві">
          </picture>
          <p class=""> Fusce ut velit laoreet, tempus arcu eu, molestie tortor. Nam vel justo cursus, faucibus lorem eget, egestas eros. Maecenas eleifend erat at justo fringilla.</p>
          <p class=""> Curabitur lacinia enim at ex blandit, vel pellentesque odio elementum. Mauris rhoncus orci in imperdiet placerat. Vestibulum euismod nisl suscipit ligula volutpat, a feugiat urna maximus. Cras massa nibh, tincidunt. Aliquam erat volutpat. Aenean accumsan.</p>
          <button class="hawe-its-made-btn" type="button">Read more</button>
        </ul>
      </div>
      <div class="container-our-advantages"> 
        <ul class="">
          <li class="">
            <picture>
              <source srcset="" media="max-width: 320px" >
              <source srcset="" media="min-width: 768px" >
              <source srcset="" media="min-width: 1200px" >
            <img class="" width="33px" height="50px" src="./images/demo.jpg" alt="графічне зображення відерка та вим'я корови.  Смачно як у дитинстві">
            </picture>
            <h3 class="">721</h3>
            <p class="">Aliquam ac dui vel dui vulputate consectetur. Mauris massa.</p>
          </li>
          <li class="">
            <picture>
              <source srcset="" media="max-width: 320px" >
              <source srcset="" media="min-width: 768px" >
              <source srcset="" media="min-width: 1200px" >
            <img class="" width="50px" height="50px" src="./images/demo.jpg" alt="графічне зображення відерка з яблуками.  Смачно як у дитинстві">
            </picture>
            <h3 class="">16kg</h3>
            <p class="">Aliquam ac dui vel dui vulputate consectetur. Mauris massa.</p>
          </li>
          <li class="">
            <picture>
              <source srcset="" media="max-width: 320px" >
              <source srcset="" media="min-width: 768px" >
              <source srcset="" media="min-width: 1200px" >
            <img class="" width="44px" height="50px" src="./images/demo.jpg" alt="графічне зображення морозива на палочці у формі серця. Смачно як у дитинстві">
            </picture>
            <h3 class="">84</h3>
            <p class="">Aliquam ac dui vel dui vulputate consectetur. Mauris massa.</p>
          </li>
        </ul>
      </div>
    </div>
    </Section>


