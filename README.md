  public static void main(String[] args) {
        char grade = 'c';
        switch (grade){
            case 'a':
                System.out.print("Excelente !");
                 break;
            case 'b':
            case 'c':
                System.out.print("Bem feito!");
                break;
            case 'd' :
                System.out.print("Você passor !");
                break;
            case 'e':
                System.out.print("Melhor tentar novamente !");
                break;
            default :
                System.out.print("Conceito inválido !");
        }
    }
    
}
