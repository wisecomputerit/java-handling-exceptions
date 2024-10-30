Contribute code

public class ExceptionHandlingExample {
    public static void main(String[] args) {

    
        int[] numbers = {1, 2, 3};

        try {
            // 可能會引發 ArrayIndexOutOfBoundsException
            System.out.println(numbers[5]); 
        } catch (ArrayIndexOutOfBoundsException e) {
            // 處理異常
            System.out.println("發生異常：數組索引超出範圍！");
        } finally {
            // 無論是否發生異常都會執行的代碼
            System.out.println("這是一條 finally 信息。");
        }

        // 繼續其他操作
        System.out.println("程序繼續執行。");
    }
}
