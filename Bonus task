import java.util.Scanner;

public class SentenceAnalyzer {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Take input
        System.out.print("Enter a sentence: ");
        String sentence = scanner.nextLine();

        // Count vowels
        int vowelCount = 0;
        for (char ch : sentence.toCharArray()) {
            if ("aeiouAEIOU".indexOf(ch) != -1) {
                vowelCount++;
            }
        }

        // Count words
        String[] words = sentence.trim().split("\\s+");
        int wordCount = words.length;

        // Output
        System.out.println("Original String: " + sentence);
        System.out.println("Length: " + sentence.length());
        System.out.println("Uppercase: " + sentence.toUpperCase());
        System.out.println("Lowercase: " + sentence.toLowerCase());
        System.out.println("Concatenated String: " + sentence + " Java");
        if (sentence.length() > 4) {
            System.out.println("Character at index 4: " + sentence.charAt(4));
        } else {
            System.out.println("Character at index 4: Index out of range");
        }
        System.out.println("Index of 'o': " + sentence.indexOf('o'));
        if (sentence.length() > 6) {
            System.out.println("Substring from index 6: " + sentence.substring(6));
        } else {
            System.out.println("Substring from index 6: ");
        }
        System.out.println("Replaced String: " + sentence.replace("World", "Java"));
        System.out.println("Number of vowels: " + vowelCount);
        System.out.println("Number of words: " + wordCount);

        scanner.close();
    }
}
