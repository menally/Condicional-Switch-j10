ublic class Main {

    public static void main(String[] args) {

        int dia = 3;

        switch (dia) {
            
                System.out.println("Lunes");
                break;

            
                System.out.println("Martes");
                break;

            
                System.out.println("Miércoles");
                break;

            default: // es cualquier otro caso
                System.out.println("Mes no válido");
        }
        System.out.println("---------------------------------");
        int meses = 3;
        switch (meses) {
            case 1:
                System.out.println("Marzo");
                break;
            case 2:
                System.out.println("Mayo");
                break;
            case 3:
                System.out.println("Diciembre");
                break;
            default:
                System.out.println("Mes no valido");
        }
        System.out.println("\n-----------\n");
    }

        }