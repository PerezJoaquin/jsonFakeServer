en AppModule importar HttpClientModule de @angular/common/http y agregarlo a imports

en el .ts importar HttpClient de la misma ruta e instanciarlo

en un metodo usar:
intanciaHttpClient.get([url y query])
.subscribe(
 (data:any[])=>{
  if(data.length){
     //lo que sea que voy a haer con los datos
  }
 }
);
