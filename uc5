public class HelloApp {
    public static void main(String[] args) {

        // Case 1: No arguments → default message
        if (args.length == 0) {
            System.out.println("Hello, World!");
            return;
        }

        // Case 2: Arguments provided → build names
        StringBuilder nameBuilder = new StringBuilder();
        boolean first = true;

        // Enhanced for loop
        for (String name : args) {
            if (!first) {
                nameBuilder.append(", ");
            }
            nameBuilder.append(name);
            first = false;
        }

        // Final output
        System.out.println("Hello, " + nameBuilder.toString() + "!");
    }
}