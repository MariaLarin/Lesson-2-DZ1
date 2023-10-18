# Lesson-2-DZ1
public class Main {


    public static <string> void main(String[] args) {

        scanner scanner= new scanner (System.in);
        System.out.print("Наименование: ");
        String Наименование = scanner.nextLine();
        System.out.print("Количество: ");
        int количество = scanner.nextint();
        System.out.print("Номер телефона: %d \n" );
        long Номер = scanner.nextlong();
        System.out.print("Адрес: ");
        String Адрес = scanner.nextLine();
        System.out.print("Ваш заказ принят. Наименование: %s в количестве: %s прибудет к вам в ближайшее время. Товар доставим по адресу: %s Ваш контактный номер: %s");
                scanner.close();
         }
}
