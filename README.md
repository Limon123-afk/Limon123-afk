  public  class  Limon123-afk soy un  extiende  Humano  implementa  Gamer , Desarrollador {

	@Override 
	public  String  getName () {
		 return  " Dani " ;
	}
	
	@Override 
	public  List< String >  getAliases () {
		 return  Arrays . asList( " Danidev819 " , " Mi Nombre " );
	}

        público  Dani () {
         super ( " Dani " , " Tierra " );

        esto _ addLanguage( " Java " , " Javascript " , " CSS " );
        esto _ addExperience( " 5 Años+(java) " , " 2 Años+(JavaScript) " , " 1 año (CSS) " ,);
     }
   }

	@Override 
	public  String aboutme() {
		 return  " Me gusta jugar Minecraft "  + 
		" \n "  +  " Me gusta programar en Java " ;
	}
    
	@Override 
	public  void codingStuff() {
		 String [] aprendizaje = [ " Java " , " Node.js / Discord.js " , " CyberSecurity " ];
		String tryTo =  " Programar lo mejor posible en clientes/plugins/mods de Minecraft " ;
	}
	
}


public  abstract  clase  Humano {

  @Getter nombre de usuario de  cadena final privada  ;
  @Getter privado Cadena final país;    

   Conjunto privado < Cadena > idiomas =  nuevo  HashSet<> ();
  Private  Set< String > experiencias =  new  HashSet<> ();

  public  Human ( String nombre de  usuario , String  placeilive ) {
       este . nombre = nombre de usuario;
      esto _ país = lugar de vida;
  }

  public  void  addLanguage ( String ... idioma ) {
       este . idiomas _ addAll(idioma);
  }
  
  public  void  addExperience ( String ... experiencia ) {
       this . experiencias _ addAll(experiencia);
  }
}
- 📫 How to reach me ...

<!---
Limon123-afk/Limon123-afk is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
