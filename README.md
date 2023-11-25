# posmotri_v_okno
Проект "Посмотри в окно"
https://github.com/VladimirChen2004/posmotri_v_okno.git


.content__card-link:hover {
  text-decoration: underline;
/*  если добавить отступ - он уберет подчеркивание у заголовка - не хватает места
  по макету двигать буквы нельзя, а костыль с hover на оболочку - вы посчитали ошибкой*/


  .content__card-link:focus-visible { 
  outline: none; 
  .content__video-card { 
    margin: 2px; 
    outline: 1px solid #fff; 
    outline-offset: 1px; 
  } 
} 
заменил данный блок на 
.content__card-link:focus-visible > .content__video-card {
  margin: 2px;
  outline: 1px solid #fff;
}
самой ссылке outline дать не получается, но focus-visible стоит на ссылке
