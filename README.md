******************M2THode por creer mon site en bootstrap ********************

1/ bs5 
2/Dans le header je mets ma nav bar 
 <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
 -navbar  ******pour déclarer la nav 
 navbar-expand-lg ************ la grandeur de la barre 
 navbar-dark  ***********le texte est noir 
  bg-dark  **************** couleur du background 
  fixed-top ***************elle est fixé  a la page 

  2/section
   <section class="bg-dark text-light p-5">
   "bg-dark **************** fond noir
   text-light texte blanc
    p-5 padding 5

    3/container **************************toujours  mettre un container pour le responsive 

    4/flexbox
    <div class="d-sm-flex align-items-center justify-content-between">
                    <div>
 5/d-sm-flex***************************display sm le format en responsive flex
  align-items-center ************************* align item dan s l'axe de y
  justify-content-between centrer dans l'axe x


 6/ <button class="btn btn-primary btn-sm p-2">
                            Viens dans monde </button>

    btn  initialisation  du bouton
    btn-primary  couleur 
    btn-sm  taille du bouton 
    p-2  padding

7/<img src="https://cdn.pixabay.com/photo/2016/03/26/13/09/workspace-1280538_1280.jpg"
                            class="img-fluid w-2 d-none d-sm-block" alt="ordi">
img-fluid taille en responsive 
w-2  width 
d-none display 
d-sm-block" display block


8/grid
<section class="p-5">****************padding de 5
 <div class="container"> pour le responsive 
      <div class="row text-center g-4"> **************la premiere ligne ou je vais mettre mes cars les unes  acoté des autres
        <div class="col-md">******voila une colonne  -md 
9/icone
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css" integrity="sha384-xeJqLiuOvjUBq3iGOjvSQSIlwrpqjSHXpduPd6rQpuiM3f5/ijby8pCsnbu5S81n" crossorigin="anonymous">