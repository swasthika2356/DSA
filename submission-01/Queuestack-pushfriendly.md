import java.util.Stack;

class PushFriendlyQueue {

    Stack<Integer> stack = new Stack<>();


    // Enqueue / Push operation
    void push(int data) {

        stack.push(data);

        System.out.println(data + " added to queue");
    }


    // Display
    void display() {

        System.out.println("Queue elements: " + stack);
    }


    public static void main(String[] args) {

        PushFriendlyQueue q = new PushFriendlyQueue();

        q.push(10);
        q.push(20);
        q.push(30);

        q.display();
    }
}
