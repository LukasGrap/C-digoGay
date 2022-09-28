# C-digoGay

import java.io.*;
import java.util.Scanner;
 class Main {
    public static final String ANSI_RESET = "\u001B[0m";
    public static final String ANSI_YELLOW = "\u001B[33m";
    public static final String ANSI_RED = "\u001B[31m";
    public static final String ANSI_GREEN = "\u001B[32m";
    public static final String ANSI_PURPLE = "\u001B[35m";
    public static final String ANSI_CYAN = "\u001B[36m";
   public static final String ANSI_BLUE = "\u001B[34m";
   public static final String ANSI_BLACK = "\u001B[30m";
   public static final String ANSI_BLACK_BACK = "\u001B[40m";
public static final String ANSI_RED_BACK = "\u001B[41m";
public static final String ANSI_GREEN_BACK = "\u001B[42m";
public static final String ANSI_YELLOW_BACK = "\u001B[43m";
public static final String ANSI_BLUE_BACK = "\u001B[44m";
public static final String ANSI_PURPLE_BACK = "\u001B[45m";
public static final String ANSI_CYAN_BACK = "\u001B[46m";
public static final String ANSI_WHITE_BACK = "\u001B[47m";
   public static final String BLACK_BOLD = "\033[1;30m";  // BLACK
    public static final String RED_BOLD = "\033[1;31m";    // RED
    public static final String GREEN_BOLD = "\033[1;32m";  // GREEN
    public static final String YELLOW_BOLD = "\033[1;33m"; // YELLOW
    public static final String BLUE_BOLD = "\033[1;34m";   // BLUE
    public static final String PURPLE_BOLD = "\033[1;35m"; // PURPLE
    public static final String CYAN_BOLD = "\033[1;36m";   // CYAN
    public static final String WHITE_BOLD = "\033[1;37m";
   public static final String BLACK_UNDERLINED = "\033[4;30m";  // BLACK
    public static final String RED_UNDERLINED = "\033[4;31m";    // RED
    public static final String GREEN_UNDERLINED = "\033[4;32m";  // GREEN
    public static final String YELLOW_UNDERLINED = "\033[4;33m"; // YELLOW
    public static final String BLUE_UNDERLINED = "\033[4;34m";   // BLUE
    public static final String PURPLE_UNDERLINED = "\033[4;35m"; // PURPLE
    public static final String CYAN_UNDERLINED = "\033[4;36m";   // CYAN
    public static final String WHITE_UNDERLINED = "\033[4;37m";
   public static final String BLACK_BRIGHT = "\033[0;90m";  // BLACK
    public static final String RED_BRIGHT = "\033[0;91m";    // RED
    public static final String GREEN_BRIGHT = "\033[0;92m";  // GREEN
    public static final String YELLOW_BRIGHT = "\033[0;93m"; // YELLOW
    public static final String BLUE_BRIGHT = "\033[0;94m";   // BLUE
    public static final String PURPLE_BRIGHT = "\033[0;95m"; // PURPLE
    public static final String CYAN_BRIGHT = "\033[0;96m";   // CYAN
    public static final String WHITE_BRIGHT = "\033[0;97m";
   public static final String BLACK_BOLD_BRIGHT = "\033[1;90m"; // BLACK
    public static final String RED_BOLD_BRIGHT = "\033[1;91m";   // RED
    public static final String GREEN_BOLD_BRIGHT = "\033[1;92m"; // GREEN
    public static final String YELLOW_BOLD_BRIGHT = "\033[1;93m";// YELLOW
    public static final String BLUE_BOLD_BRIGHT = "\033[1;94m";  // BLUE
    public static final String PURPLE_BOLD_BRIGHT = "\033[1;95m";// PURPLE
    public static final String CYAN_BOLD_BRIGHT = "\033[1;96m";  // CYAN
    public static final String WHITE_BOLD_BRIGHT = "\033[1;97m";
   public static final String BLACK_BACKGROUND_BRIGHT = "\033[0;100m";// BLACK
    public static final String RED_BACKGROUND_BRIGHT = "\033[0;101m";// RED
    public static final String GREEN_BACKGROUND_BRIGHT = "\033[0;102m";// GREEN
    public static final String YELLOW_BACKGROUND_BRIGHT = "\033[0;103m";// YELLOW
    public static final String BLUE_BACKGROUND_BRIGHT = "\033[0;104m";// BLUE
    public static final String PURPLE_BACKGROUND_BRIGHT = "\033[0;105m"; // PURPLE
    public static final String CYAN_BACKGROUND_BRIGHT = "\033[0;106m";  // CYAN
    public static final String WHITE_BACKGROUND_BRIGHT = "\033[0;107m";
    public static void main(String[] args)
    {
      Scanner input = new Scanner(System.in);
      int x;
      System.out.println("Qual bandeira você quer ver?"); //concluído
      System.out.println("Gay[1]"); //concluído
      System.out.println("Trans[2]"); //concluído
      System.out.println("Bissexual[3]"); //concluído
      System.out.println("Panssexual[4]");  //concluído
      System.out.println("Não-binária[5]");  //concluído
      System.out.println("Lésbica[6]");  //concluído
      System.out.println("Queer[7]");  //concluído
      System.out.println("Gênero-fluido[8]"); //concluído
      System.out.println("Assexual[9]"); //concluído
      System.out.println("Arromântica[10]"); //concluído
      System.out.println("Intersexo[11]"); //concluído
      System.out.println("Demissexual[12]"); //concluído
      System.out.println("Demirroântica[13]");  //concluído
      System.out.println("Demi-girl[14]"); //concluído
      System.out.println("Demi-boy[15]"); //concluído
      System.out.println("Agênero[16]"); //concluído
      System.out.println("Bigênero[17]"); //concluído
      System.out.println("Todas[18]"); //concluído
      System.out.println(" ");
      System.out.print("Resposta: ");
      x = input.nextInt();
      if (x == 18) {
        System.out.println(RED_BOLD + "===========================" + ANSI_RESET);  //gay-LGBT+
      System.out.println(RED_BRIGHT + "===========================" + ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT + "===========================" + ANSI_RESET);
      System.out.println(GREEN_BOLD + "===========================" + ANSI_RESET);
      System.out.println(BLUE_BOLD + "===========================" + ANSI_RESET);
      System.out.println(ANSI_PURPLE + "===========================" + ANSI_RESET);
      System.out.print(RED_BOLD + "          a" + ANSI_RESET);
      System.out.print(RED_BRIGHT + "m" + ANSI_RESET);
      System.out.print(YELLOW_BOLD_BRIGHT + "o " + ANSI_RESET);
      System.out.print(GREEN_BOLD +"v"+ ANSI_RESET);
      System.out.print(BLUE_BOLD +"c"+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"!"+ ANSI_RESET);
      System.out.println(BLUE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);  //transgênero
      System.out.println(RED_BOLD_BRIGHT +   "==========================="+ ANSI_RESET);
      System.out.println("===========================");
      System.out.println(RED_BOLD_BRIGHT +   "==========================="+ ANSI_RESET);
      System.out.println(BLUE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.print(BLUE_BOLD_BRIGHT +"       In"+ ANSI_RESET);
      System.out.print(RED_BOLD_BRIGHT +"den"+ ANSI_RESET);
      System.out.print("pen");
      System.out.print(RED_BOLD_BRIGHT +"den"+ ANSI_RESET);
      System.out.println(BLUE_BOLD_BRIGHT +"te"+ ANSI_RESET);
      System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);  //bissexual
      System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
      System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
      System.out.println(ANSI_BLUE +"==========================="+ ANSI_RESET);
      System.out.println(ANSI_BLUE +"==========================="+ ANSI_RESET);
      System.out.print("     De quem você ");
      System.out.print(PURPLE_BOLD_BRIGHT +"a"+ ANSI_RESET);
      System.out.print(PURPLE_BOLD +"m"+ ANSI_RESET);
      System.out.print(ANSI_BLUE +"a"+ ANSI_RESET);
      System.out.println("!");
      System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);  //pansexual
      System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
      System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
      System.out.print(PURPLE_BOLD_BRIGHT +"       Inden"+ ANSI_RESET);
      System.out.print(YELLOW_BOLD_BRIGHT +"pen"+ ANSI_RESET);
      System.out.println(BLUE_BOLD +"dente"+ ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT +"==========================="+ ANSI_RESET); //Não-binário
      System.out.println("===========================");
      System.out.println(ANSI_PURPLE +"==========================="+ ANSI_RESET);
      System.out.println(BLACK_BOLD +"==========================="+ ANSI_RESET);
      System.out.print(YELLOW_BOLD_BRIGHT +"      De "+ ANSI_RESET);
      System.out.print("quem ");
      System.out.print(ANSI_PURPLE +"você "+ ANSI_RESET);
      System.out.println(BLACK_BOLD +"é!"+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET); //linha1 lésbica
      System.out.print(ANSI_PURPLE +"======="+ ANSI_RESET); //linha2
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"======"+ ANSI_RESET); //linha3
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"==========="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======"+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET); //linha4
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET); //linha5
      System.out.print(BLACK_BOLD +"========"+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"========"+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET); //linha 6
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"==="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"==="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"======"+ ANSI_RESET); //linha7
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======"+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"======="+ ANSI_RESET); //linha8
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha9
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha10
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha11
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha12
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET);
        System.out.print(ANSI_PURPLE+"Eu "+ANSI_RESET);
        System.out.print(BLACK_BOLD+"te "+ANSI_RESET);
        System.out.println(ANSI_PURPLE+"apoio!"+ANSI_RESET);
        System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET); //queer
        System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET);
        System.out.println("=============================");
        System.out.println("=============================");
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET);
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET);
        System.out.print(ANSI_PURPLE +"Eu "+ ANSI_RESET);
        System.out.print("te ");
        System.out.println(GREEN_BOLD+"respeito!"+ANSI_RESET);
        System.out.println(PURPLE_BOLD_BRIGHT +"============================="+ ANSI_RESET);//Gênero-fluído
        System.out.println("=============================");
        System.out.println(PURPLE_BOLD +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
        System.out.println(ANSI_BLUE +"============================="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD_BRIGHT+"Porque "+ANSI_RESET);
        System.out.print("somos ");
        System.out.print(PURPLE_BOLD +"iguais "+ANSI_RESET);
        System.out.print(BLACK_BOLD+"mesmo "+ANSI_RESET);
        System.out.println(ANSI_BLUE +"diferentes :)"+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET); //Assexual
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
          System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println("=============================");
        System.out.println("=============================");
        System.out.println(PURPLE_BOLD +"============================="+ ANSI_RESET);
        System.out.println(PURPLE_BOLD +"============================="+ ANSI_RESET);
        System.out.print(BLACK_BOLD+"Você "+ANSI_RESET);
        System.out.print(BLACK_BOLD_BRIGHT+"é "+ANSI_RESET);
        System.out.print("especial ");
        System.out.println(PURPLE_BOLD +"pra mim!"+ ANSI_RESET);
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET); //arromântica
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET);
        System.out.println(GREEN_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(GREEN_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println("=============================");
        System.out.println("=============================");
        System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
        System.out.print(GREEN_BOLD+"Por "+ANSI_RESET);
        System.out.print(GREEN_BOLD_BRIGHT+"você "+ANSI_RESET);
        System.out.print("me ");
        System.out.print(BLACK_BOLD_BRIGHT+"fazer "+ANSI_RESET);
        System.out.println(BLACK_BOLD+"mais feliz :)"+ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"============================="+ ANSI_RESET); //linha1-intersexo
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET); //linha2
        System.out.print(PURPLE_BOLD +"======="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET); //linha3
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET); //linha4
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET); //linha5
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======"+ ANSI_RESET); //linha6
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"============="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"======"+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET); //linha7
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET); //linha8
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET); //linha9
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET); //linha10
        System.out.print(PURPLE_BOLD +"======="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"============================="+ ANSI_RESET); //linha11
        System.out.print(YELLOW_BOLD_BRIGHT+"Você "+ANSI_RESET);
        System.out.println(PURPLE_BOLD+"importa!!"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha1DS
        System.out.println("========================================");
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha2
        System.out.println("======================================");
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha3
        System.out.println("====================================");
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha4
        System.out.println("==================================");
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha5
        System.out.println("================================");
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha6
        System.out.println("==============================");
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha7
        System.out.println("============================");
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha8
        System.out.println(PURPLE_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha9
        System.out.println(PURPLE_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==================="+ANSI_RESET);//linha10
        System.out.println(PURPLE_BOLD+"======================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha11
        System.out.println(PURPLE_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha12
        System.out.println(PURPLE_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha13
        System.out.println(BLACK_BOLD_BRIGHT+"============================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha14
        System.out.println(BLACK_BOLD_BRIGHT+"=============================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha15
        System.out.println(BLACK_BOLD_BRIGHT+"================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha16
        System.out.println(BLACK_BOLD_BRIGHT+"=================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha17
        System.out.println(BLACK_BOLD_BRIGHT+"===================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha18
        System.out.println(BLACK_BOLD_BRIGHT+"======================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha19
        System.out.println(BLACK_BOLD_BRIGHT+"========================================"+ANSI_RESET);
        System.out.println("");
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha1DR
        System.out.println("========================================");
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha2
        System.out.println("======================================");
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha3
        System.out.println("====================================");
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha4
        System.out.println("==================================");
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha5
        System.out.println("================================");
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha6
        System.out.println("==============================");
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha7
        System.out.println("============================");
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha8
        System.out.println(GREEN_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha9
        System.out.println(GREEN_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==================="+ANSI_RESET);//linha10
        System.out.println(GREEN_BOLD+"======================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha11
        System.out.println(GREEN_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha12
        System.out.println(GREEN_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha13
        System.out.println(BLACK_BOLD_BRIGHT+"============================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha14
        System.out.println(BLACK_BOLD_BRIGHT+"=============================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha15
        System.out.println(BLACK_BOLD_BRIGHT+"================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha16
        System.out.println(BLACK_BOLD_BRIGHT+"=================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha17
        System.out.println(BLACK_BOLD_BRIGHT+"===================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha18
        System.out.println(BLACK_BOLD_BRIGHT+"======================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha19
        System.out.println(BLACK_BOLD_BRIGHT+"========================================"+ANSI_RESET);
        System.out.println(" ");
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(RED_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println("===========================");
        System.out.println(RED_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(" ");
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLUE_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println("===========================");
        System.out.println(BLUE_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(" ");
        System.out.println(BLACK_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println("===========================");
        System.out.println(GREEN_BOLD_BRIGHT+"==========================="+ANSI_RESET);
       System.out.println("===========================");
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(" ");
        System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET); System.out.println(YELLOW_BOLD_BRIGHT+"==========================="+ANSI_RESET); System.out.println(YELLOW_BOLD_BRIGHT+"==========================="+ANSI_RESET);
        System.out.println("===========================");
        System.out.println("===========================");
        System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
    }
      if (x == 1) {
        System.out.println(RED_BOLD + "===========================" + ANSI_RESET);  //gay-LGBT+
      System.out.println(RED_BRIGHT + "===========================" + ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT + "===========================" + ANSI_RESET);
      System.out.println(GREEN_BOLD + "===========================" + ANSI_RESET);
      System.out.println(BLUE_BOLD + "===========================" + ANSI_RESET);
      System.out.println(ANSI_PURPLE + "===========================" + ANSI_RESET);
      }
      if (x == 2) {
        System.out.println(BLUE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);  //Transgênero
      System.out.println(RED_BOLD_BRIGHT +   "==========================="+ ANSI_RESET);
      System.out.println("===========================");
      System.out.println(RED_BOLD_BRIGHT +   "==========================="+ ANSI_RESET);
      System.out.println(BLUE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      }
      if (x == 3) {
        System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET); //Bissexual
      System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
      System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
      System.out.println(ANSI_BLUE +"==========================="+ ANSI_RESET);
      System.out.println(ANSI_BLUE +"==========================="+ ANSI_RESET);
      }
      if (x == 4) {
        System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET); //Pansexual
      System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(YELLOW_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
      System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
      System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
      }
      if (x == 5) {
      System.out.println(YELLOW_BOLD_BRIGHT +"==========================="+ ANSI_RESET);//Não-binárie
      System.out.println("===========================");
      System.out.println(ANSI_PURPLE +"==========================="+ ANSI_RESET);
      System.out.println(BLACK_BOLD +"==========================="+ ANSI_RESET);
      }
      if (x == 6) {
      System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET); //linha1 - lésbica
      System.out.print(ANSI_PURPLE +"======="+ ANSI_RESET); //linha2
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"======"+ ANSI_RESET); //linha3
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"==========="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======"+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET); //linha4
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET); //linha5
      System.out.print(BLACK_BOLD +"========"+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"========"+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET); //linha 6
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"==="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"==="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"====="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"======"+ ANSI_RESET); //linha7
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"===="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======"+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"======="+ ANSI_RESET); //linha8
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"====="+ ANSI_RESET);
      System.out.print(BLACK_BOLD +"="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"======="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha9
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha10
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha11
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.print(ANSI_PURPLE +"============="+ ANSI_RESET); //linha12
      System.out.print(BLACK_BOLD +"==="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============="+ ANSI_RESET);
      System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET);
      }
      if (x == 7) {
        System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET); //Queer
        System.out.println(ANSI_PURPLE +"============================="+ ANSI_RESET);
        System.out.println("=============================");
        System.out.println("=============================");
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET);
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET);
      }
      if (x == 8) {
        System.out.println(PURPLE_BOLD_BRIGHT +"============================="+ ANSI_RESET); //Gênero-fluído
        System.out.println("=============================");
        System.out.println(PURPLE_BOLD +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
        System.out.println(ANSI_BLUE +"============================="+ ANSI_RESET);
      }
      if (x == 9) {
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET); //Assexual
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
          System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println("=============================");
        System.out.println("=============================");
        System.out.println(PURPLE_BOLD +"============================="+ ANSI_RESET);
        System.out.println(PURPLE_BOLD +"============================="+ ANSI_RESET);
      }
      if (x == 10) {
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET); //arromântica
        System.out.println(GREEN_BOLD +"============================="+ ANSI_RESET);
        System.out.println(GREEN_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(GREEN_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println("=============================");
        System.out.println("=============================");
        System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"============================="+ ANSI_RESET);
      }
      if (x == 11) {
        System.out.println(YELLOW_BOLD_BRIGHT +"============================="+ ANSI_RESET); //linha1-intersexo
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET); //linha2
        System.out.print(PURPLE_BOLD +"======="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET); //linha3
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET); //linha4
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET); //linha5
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======"+ ANSI_RESET); //linha6
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"============="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"======"+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET); //linha7
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET); //linha8
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========"+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET); //linha9
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"======="+ ANSI_RESET);
        System.out.print(PURPLE_BOLD +"=="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"========="+ ANSI_RESET);
        System.out.print(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET); //linha10
        System.out.print(PURPLE_BOLD +"======="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"==========="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT +"============================="+ ANSI_RESET); //linha11
      }
      if (x == 12) {
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha1DS
        System.out.println("========================================");
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha2
        System.out.println("======================================");
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha3
        System.out.println("====================================");
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha4
        System.out.println("==================================");
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha5
        System.out.println("================================");
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha6
        System.out.println("==============================");
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha7
        System.out.println("============================");
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha8
        System.out.println(PURPLE_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha9
        System.out.println(PURPLE_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==================="+ANSI_RESET);//linha10
        System.out.println(PURPLE_BOLD+"======================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha11
        System.out.println(PURPLE_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha12
        System.out.println(PURPLE_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha13
        System.out.println(BLACK_BOLD_BRIGHT+"============================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha14
        System.out.println(BLACK_BOLD_BRIGHT+"=============================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha15
        System.out.println(BLACK_BOLD_BRIGHT+"================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha16
        System.out.println(BLACK_BOLD_BRIGHT+"=================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha17
        System.out.println(BLACK_BOLD_BRIGHT+"===================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha18
        System.out.println(BLACK_BOLD_BRIGHT+"======================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha19
        System.out.println(BLACK_BOLD_BRIGHT+"========================================"+ANSI_RESET);
      }
      if (x == 13) {
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha1DR
        System.out.println("========================================");
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha2
        System.out.println("======================================");
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha3
        System.out.println("====================================");
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha4
        System.out.println("==================================");
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha5
        System.out.println("================================");
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha6
        System.out.println("==============================");
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha7
        System.out.println("============================");
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha8
        System.out.println(GREEN_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha9
        System.out.println(GREEN_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==================="+ANSI_RESET);//linha10
        System.out.println(GREEN_BOLD+"======================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"================="+ANSI_RESET);//linha11
        System.out.println(GREEN_BOLD+"========================"+ANSI_RESET); 
        System.out.print(BLACK_BOLD+"==============="+ANSI_RESET);//linha12
        System.out.println(GREEN_BOLD+"=========================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"============="+ANSI_RESET);//linha13
        System.out.println(BLACK_BOLD_BRIGHT+"============================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==========="+ANSI_RESET);//linha14
        System.out.println(BLACK_BOLD_BRIGHT+"=============================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"========="+ANSI_RESET);//linha15
        System.out.println(BLACK_BOLD_BRIGHT+"================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"======="+ANSI_RESET);//linha16
        System.out.println(BLACK_BOLD_BRIGHT+"=================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"====="+ANSI_RESET);//linha17
        System.out.println(BLACK_BOLD_BRIGHT+"===================================="+ANSI_RESET);
        System.out.print(BLACK_BOLD+"==="+ANSI_RESET);//linha18
        System.out.println(BLACK_BOLD_BRIGHT+"======================================"+ANSI_RESET);
        System.out.print(BLACK_BOLD+"="+ANSI_RESET);//linha19
        System.out.println(BLACK_BOLD_BRIGHT+"========================================"+ANSI_RESET);
      }
      if (x == 14) {
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(RED_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println("===========================");
        System.out.println(RED_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
      }
      if (x == 15) {
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLUE_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println("===========================");
        System.out.println(BLUE_BRIGHT +"==========================="+ANSI_RESET);
        System.out.println(BLACK_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
      }
      if (x == 16) {
        System.out.println(BLACK_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println("===========================");
        System.out.println(GREEN_BOLD_BRIGHT+"==========================="+ANSI_RESET);
       System.out.println("===========================");
        System.out.println(BLACK_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(BLACK_BOLD +"==========================="+ ANSI_RESET);
      }
      if (x == 17) {
        System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(PURPLE_BOLD_BRIGHT +"==========================="+ ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT+"==========================="+ANSI_RESET);
        System.out.println(YELLOW_BOLD_BRIGHT+"==========================="+ANSI_RESET);
        System.out.println("===========================");
        System.out.println("===========================");
        System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(PURPLE_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
        System.out.println(BLUE_BOLD +"==========================="+ ANSI_RESET);
      }
  }
}
