# idiomadosistemaJAVA



package sistemaidioma;

import java.util.Locale;

public class Sistemaidioma {

public static void main(String[] args) {


    Locale idioma = Locale.getDefault();
    System.out.println("Idioma: "+ idioma.getDisplayLanguage() +" "+ idioma.getLanguage());

}
    
}

