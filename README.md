# Assignment-4-java
Write a program to search for a specific element in a priority queue
import java.util.PriorityQueue;

public class PriorityQueueSearch {
    public static void main(String[] args) {
        PriorityQueue<Integer> pq = new PriorityQueue<>();

        // Adding elements to the priority queue
        int[] elements = {5, 3, 9, 1, 7};
        for (int el : elements) {
            pq.add(el);
        }

        // Display the priority queue
        System.out.println("Priority Queue elements: " + pq);

        // Search for a specific element
        int target = 9;
        if (pq.contains(target)) {
            System.out.println("Element " + target + " found in the priority queue.");
        } else {
            System.out.println("Element " + target + " not found in the priority queue.");
        }
    }
}
