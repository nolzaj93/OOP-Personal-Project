# OOP-Personal-Project
## Artificial Intelligence with Machine Learning in Java 2019 
Applying concepts learned in the Oracle iLearning AI with Machine Learning Course

#### Week 1 - Section 1 Introduction (4 hours)
- Read through 1.1, 1.2, 1.3, and 1.4

##### 1.2
- Goal of AI is building machines to behave intelligently
- Turing Test: if an observer of a conversation between a computer and a human cannot differentiate which one is human, then the computer passes the test.
- Artificial Intelligence: attempt to build machines capable of simulating intelligent human behavior.
- AI machines are built through the use of Machine Learning (focus of this course) or with other approaches, like Deep Learning
- Machine learning: science of getting computers to act without being explicitly programmed - Stanford University.
- ML programs aim to gain information that can be used against another similar problem.
- wiki definition- machine learning explores the study and construction of algorithms that can learn from and make predictions on data.
-Applications of AI and ML: face identification, Facebook advertisements, Netflix personalized suggestion, Amazon purchase suggestions.

###### Task - 3 scenarios that use Machine Learning
- Speech-to-text saves time typing
- Face detection/recognition improves security, reduces crime.
- GPS can avoid time spent in traffic
- Others -Virtual Personal Assistants, Video Surveillance, Online Fraud Detection, Healthcare, Financial Trading, Smart Cars

- Data Exhaust: trails of data you leave behind which constantly gives you information throughout the day
##### 1.3
- The data from users is what is feeding the growth of Machine Learning
- Data is the raw figures/facts while information is the data presented in context 
- Collection of facts (data) vs. Printing label (Information)

###### Task - Data or information
All student marks- Data
Average of student marks- Information
Country of all visitors to a website- Data
Total visitors to a website by country - Information
Total sales by day- Information
Time and data of a sale transaction- Data
Student data on an enrollment form- Data
Student address on a label- information

##### 1.4
- Machine Learning : "intelligent machines" are all ran by algorithms and require input of some form to learn (voice, files, internet searches, electronic instruments, etc.)
- ML algorithms are split into two categories : supervised and unsupervised learning
- Supervised learning : occurs when information is available, but not enough information to learn until more data is gathered. There is a known label(property or result set) that can feed it data from a training set (data). Examples: loan approval decision based on dependent data like age, credit rating, etc, or an email spam filter which asks you to report spam. Training data ("learning") and test data (accuracy) are used to improve the algorithm which is called generalization.
- Generalization (ability of an algorithm to be generalized to new data) and Overfitting (when a model is trained too well on training data and is unable to generalize.
- https://wp.wwu.edu/machinelearning/2017/01/22/generalization-and-overfitting/
- Goal - produce good test data for the generalization models, while maintaining flexibility with new data
- Independent data (predictors used to determine target/outcome) vs. dependent data (target/outcome of application is dependent on independent data)
- Supervised Learning: data stored in a label falls into these two categories
- Classification -independent data is defined as a class label with a discrete value, output variable is a category. The prediction data (dependent data) is output.
- Regression -output variable is a real value such as "dollars" or "weight" (https://www.geeksforgeeks.org/regression-classification-supervised-machine-learning/)
- ranges of data stored using real numbers, continuous not discrete
- Predictions from regression range could also be a range rather than a closed set
- In many cases you can change a regression to classification
- Supervised learning and Structured Data are focused on in this course

- Unsupervised Learning - structure of data is unknown, no known labels or classifications. These algorithms make inferences typically from big datasets.

###### Task
- Temperature - 26,24,23,26 Regression
- Age - 22,45,22,30 Regression
- Age - Young, Middle, Old Classification
- House Value - 100000,150000,120000 Regression
- House Value - Low, Middle, High, Very High Classification
- Animal - Cat, Dog, Fish Classification
- Eye color- Blue, Green, Brown Classification

- Structured data -high degree of organization with each item fitting into a type. Ex. numbers, dates, normally displayed in table format  
- Unstructured Data -data that does not conform to the rules of Structured Data. Ex. email message, text, pictures, multimedia messages, sound

- Steps to look at Structured Data
- Collect input and result examples
- Make a model from the examples
- Add new inputs (test data) to the model
- Test the results (outputs) from the model and evaluate 

###### Task
1. Examples of classification: Age, Has Job, Owns House, Credit Rating
2. Young, No, No, Fair
3. Dependent data is determined by the independent data, so the classifications of age, has job, owns house, and credit rating are used to determine a loan approval for rows 3,5, and 6.

- Labels (classifications) - composed of both independent and dependent data
##### Section 2 (2 hours)
##### 2.1 
- Why Now? Collection of data has become more accurate and frequent, many facets of our lives are recorded in huge quantities, so we require Machine Learning to help turn big data into useful information.
- Computational Power - increase in processing power and cloud storage make it possible to process massive amounts of data faster, so ML algorithms allow us to understand and analyze data faster.
- Opportunities - explosion of jobs in the area of big data and software to deal with it, which will allow companies to understand their markets better and make more strategic decisions. 
- Comparing Tech Over Time - iPhone 4 has 2.7 times the processing power of a 1985 Cray-2 supercomputer, which could fill a small room.
- Nintendo Entertainment System released in 1985 contained half of the processing power of the Apollo computer Guidance system
- Took around 15 years for a home product to match what was the fastest super computer available at the time (also greatly reduced size in that time)
- Moore's Law - In 1965, Gordon E. Moore, co-founder of Intel, had an insight that the number of transistors per integrated circuit will double about every two years. This held true from 1975 to 2012, and Intel said 2015 their pace of advancement has slowed.

##### 2.2 Machine Learning Workflow
- Objectives - Understand the use of models within machine learning and the CRISP-DM model

###### Machine Learning Workflow
- Identify the entire process for a ML solution to complete a project. There obviously must be an unsolved problem or an opportunity to understand it better. 
- ML needs data input, computational power, and algorithms as a start to solving/understanding the problem
- goal of ML is the correct interpretation of results

###### Models
- Many models in data science regarding ML, like CRISP-DM (Cross-Industry Standard Process for Data Mining), which has 6 stages

###### CRISP Stages
- Business understanding - What question(s) need to be answered? <--> 
- Data understanding - Where will the data originate? -->
- Data preparation - What data is required? <-->
- Modeling - What machine learning will be used? -->
- Evaluation- Evaluate results of the machine learning -->
- The first five steps are cyclical
- Deployment - Push out the solution

###### CRISP Steps for Loan Application
- Example: Bank has processed loan applications over a number of years which provides data for use in modelling.
- Step 1 - should the application be approved?
- Step 2 - use data and outcomes from previous applications 
- Step 3 - Required criteria: Salary, contract length, outstanding loans, credit history
- Step 4 - ML approach(es) which fits this scenario best
- Step 5 - Evaluate the results of the ML algorithm by using learning and test data

###### Public Data Sets
- http://archive.ics.uci.edu/ml/datasets.html
- This lists data sets where ML could be applied to analyze and predict outcomes

###### Task
- A reason to work with this data set would be to better filter out phishing emails.
- https://archive.ics.uci.edu/ml/datasets/Website+Phishing

##### Section 1 and 2 Quiz (30 Minutes)

Test Summary: Sections 1 & 2 Quiz
	
	Section 1 	
	11 	11
	[Answered] 	     What is data exhaust? 	        Yes 	1 	1
	[Answered] 	     Which of the following is the... 	Yes 	1 	1
	[Answered] 	     Average results for a class i... 	Yes 	1 	1
	[Answered] 	     What does data mean? 	        Yes 	1 	1
	[Answered] 	     Recording the tempearture eve... 	Yes 	1 	1
	[Answered] 	     In a loan example "has job is... 	Yes 	1 	1
	[Answered] 	     Classification of data is whe... 	Yes 	1 	1
	[Answered] 	     Rainfall recorded as 2,3,0,3,... 	Yes 	1 	1
	[Answered] 	     You watch a baseball game wit... 	Yes 	1 	1
	[Answered] 	     Regression of data is when 	Yes 	1 	1
	[Answered] 	     Is raw processing power a dem... 	Yes 	1 	1
	Section 2 	
	4 	4
	[Answered] 	     Cloud computing is one of the... 	Yes 	1 	1
	[Answered] 	     In the CRIP model we cannot m... 	Yes 	1 	1
	[Answered] 	     In the CRISP model, how would... 	Yes 	1 	1
	[Answered] 	     The single most important thi... 	Yes 	1 	1

##### Section 3: Trees and Recursion
##### - Sections 3.1 and 3.2(1.5 hours)

##### 3.1 Binary Trees
- Decision Tree Algorithms - construct a model based on answers (or values) from data.
- Binary Trees - a data structure composed of nodes, each of which has a left and right reference to other nodes. A tree is constrained to all nodes having a maximum of 2 child nodes.
- First nodes is called the root node, and is the building block of all others
- Every other node must be connected to a parent node
- Nodes can have 0-2 child nodes, and a node with no children is called a leaf
- Nodes with the same parent are called siblings

###### Task
1. What is the parent of 6? Node #3
2. What is 1 the parent of? Nodes #2 and #3
3. Explain the relationships of 5. Node #5 has a sibling (#4), a child (#7), and a parent (#2).

- Binary trees are useful for linked hierarchies. We create a class called Node and each instance represents a node on the tree. The node's stored ata type can be anything, and could be designed first as generic, then set the specific data type at design time.
- Node objects will have a left and right property, and if it is a leaf then it will be null.
```
public class Node{
  int data;
  Node left;
  Node right;
  
  public Node(int data) {
  	this.data = data;
	left = null;
	right = null;
  }
  
  public void setLeft(Node node) {
  	if (left == null)
	  left = node;
  }
  
   public void setRight(Node node) {
  	if (right == null)
	  right = node;
  }
  
  public Node getLeft() {
  	return left;
  }
  
  public Node getRight() {
  	return right;
  }
  
  public int getData() {
  	return data;
  }
  
  public void setData(int data) {
  	this.data = data;
  }
}
```
- Tree Methods - parentNode.setLeft(childNode) and setRight(childNode) assigns the argument to the respective field, Node left or Node right. Node getLeft() and Node getRight() returns the Node object stored in those variables. To set and get data in the current node call setData(data) and getData(data).

##### 3.2 Recursion
- Recursion - when a method makes a call to itself
- Useful for data structures like trees because it makes code smaller and more readable. However, these methods can be difficult to write and may take a while to get working. Infinite loops are easy to write on accident with recursion.
- Recursion Base Case - the base case and recursive case must be defined. 
- Base case - ends the recursion which prevents an infinite loop, and is often when a value of 1 or 0 is reached.
- Recursion breaks problems down until it becomes smaller and smaller until the base care is met.

- Non-recursive power method

```
 int power(int a, int n) {
   int result = 1;
   for(int i=0;i<n;i++) {
 	result *=a;
   }
 
 }
```

- Recursive power method
```
 int power(int a, int n) {
   if (n == 0) {
   	return 1;
   } else {
   	return a * power(a, n-1);
   }
 }
```
- If we call power(2,3) with the recursive method then we see the following process
1. power(2,0) (the base case) returns 1 to power(2,1)
2. power(2,1) returns 2 to power(2,2)
3. power(2,2) returns 4 to power(2,3)
4. 8 is the result returned

- Every call to itself creates a new copy that has its own local variables and parameters.
- Memory Issues - in a recursive solution, much more memory is required as the number of calls increases and could eventually lead to a StackOverflowError, or delay in creating a method

###### Task

- Factorial Solution 
```
 public static int factorial(int n) {
 	if(n == 1) {
	    return 1;
	}
	return n * factorial(n-1);
 }
```
- Fibonacci Solution
```
 public static int Fibonacci (int x) {
 	if( x < 2) {
	    return 1;
	} else {
	    return Fibonacci(x-1) + Fibnocci(x-2);
	}
 }
```
##### Sections 3.3 and 3.4 

##### Section 3.3 Tree Traversal (2 hours)
- Recursion allows us to navigate a tree structure to search for an item or print all nodes (tree traversal)
- Binary Trees - can be navigated many ways starting from root, print algorithms are defined for trees
- Pre-Order Traversal - print any given node before printing its children, and process to the left first: Parent, Left, Right
- Post-Order Traversal - print each node only after printing its children, process to the left first: Left, Right, Parent
- In-Order Traversal - prints left child and subtree, print the node, and then visit the right child: Left, Parent, Right

###### Task - Recursive Tree Traversal
```
public class Node{
  int data;
  Node left;
  Node right;
  
  public Node(int data) {
  	this.data = data;
	left = null;
	right = null;
  }
  
  public void setLeft(Node node) {
  	if (left == null)
	  left = node;
  }
  
   public void setRight(Node node) {
  	if (right == null)
	  right = node;
  }
  
  public Node getLeft() {
  	return left;
  }
  
  public Node getRight() {
  	return right;
  }
  
  public int getData() {
  	return data;
  }
  
  public void setData(int data) {
  	this.data = data;
  }
  
  public void printPreorder(Node node) {
  	
// 	while(node.getLeft() != null) {
//		System.out.print(node.getData() + ", " + getLeft().getData());
//		node = getLeft();
//	}
	
	if (node == null)
		return;
		
	System.out.print(node.data + " ");
	printPreorder(node.left);
	printPreorder(node.right);
  }
  
  public void printPostorder(Node node) {
  	if (node == null)
		return;
	
	printPostorder(node.left);
	printPostorder(node.right);
	System.out.print(node.data + " ");
  }
  
  public void printInorder(Node node) {
  	if (node == null)
		return;
		
	printInorder(node.left);
	System.out.print(node.data + " ");
	printInorder(node.right);
  }
}
```

- Driver Class
```

public class NodeDriver {

    public static void main(String[] args) {
	// write your code here
        Node root = new Node(1);
        Node node2 = new Node(2);
        root.setLeft(node2);
        Node node3 = new Node(3);
        root.setRight(node3);

        Node node4 = new Node(4);
        node2.setLeft(node4);

        Node node5 = new Node(5);
        node2.setRight(node5);

        Node node6 = new Node(6);
        node3.setRight(node6);

        Node node7 = new Node(7);
        node5.setLeft(node7);

        root.printPreorder(root);
	System.out.println();
	root.printPostorder(root);
	System.out.println();
	root.printPreorder(root);
    }
}

```
- Binary Trees - multiple ways to print the contents of nodes with recursive approaches

- BTree Class
```
package com.company;

public class BTree {

  private Node root;
  private Node currentNode;

  public BTree() {
    root = null;
  }

  // Search for a node that contains a particular value
  public boolean search(int data) {
    return search(root,data);
  }

  private boolean search(Node node, int data) {
    if (node.getData() == data)
      return true;
    if (node.getLeft() != null)
      if(search(node.getLeft(), data))
        return true;
      if(node.getRight() != null)
        if(search(node.getRight(),data))
          return true;
      return false;
  }

  //A helped method to call printInorder from node
  public void printInOrder() {
    root.printInorder(root);
  }

  public void printPreOrder() {
    root.printPreorder(root);
  }

  public void printPostOrder() {
    root.printPostorder(root);
  }

  public Node getRoot() {

    return root;
  }

  public void setRoot(Node root) {
    this.root = root;
  }

  public boolean isEmpty() {
    return root == null;
  }

  public int countNodes() {

    return countNodes(root);
  }

  private int countNodes(Node node) {
    int count = 1;
    if (node == null) {
      return 0;
    } else {
      count += countNodes(node.getLeft());
      count += countNodes(node.getRight());
      return count;
    }
  }

  public void print() {
    root.print();
  }

  public Node getCurrent() {
    return currentNode;
  }

  public void setCurrent(Node node) {
    this.currentNode = node;
  }
}
```

- Driver Class for BTree
```
package com.company;

public class TreeDriver {

    public static void main(String[] args) {
      System.out.println("Creating Tree");
      BTree tree = new BTree();

      System.out.println("Count nodes in empty tree");
      System.out.println(tree.countNodes());

      System.out.println("Create Nodes with data 1");
      Node root = new Node(1);

      System.out.println("Set node as root");
      tree.setRoot(root);

      System.out.println("Count nodes in tree with only root added");
      System.out.println(tree.countNodes());
      Node node2 = new Node(2);
      Node node3 = new Node(3);
      Node node4 = new Node(4);
      Node node5 = new Node(5);
      Node node6 = new Node(6);
      Node node7 = new Node(7);

      root.setLeft(node2);
      root.setRight(node3);
      node2.setLeft(node4);
      node2.setRight(node5);
      node3.setRight(node6);
      node5.setLeft(node7);

      System.out.println("Set the current node to be the root");
      tree.setCurrent(tree.getRoot());

      System.out.println("Display the current node");
      System.out.println(tree.getCurrent().getData());

      Node currentNode = tree.getCurrent();

      System.out.println("Count nodes in tree with 7 nodes added");
      System.out.println(tree.countNodes());

      System.out.println("In Order print");
      tree.printInOrder();

      System.out.println("\nPre Order print");
      tree.printPreOrder();

      System.out.println("\nPost Order print");
      tree.printPostOrder();

      System.out.println("\nDisplay the nodes as tree diagram");
      tree.print();
    }
}
```

##### Section 3.4 Yes/No Game (4 hours)
- Yes/No game where user is asked a series of yes or no questions about which animal they are thinking about. 

###### Task
- If computer guesses correctly, then the computer wins.
- If the computer does not guess correctly, then the player wins and the program "learns" where they went wrong.
- At the start, the computer will know to only ask one question, but will not know the answer to it.
- With Manual Decision Trees, it is more efficient to know the ideal first question and the order of the subsequent questions.
- Solution can ask 20 questions, and we will use sample data to determine which questions hold highest priority (information entropy).
- Decision Trees Data Set - data set used to create the decision tree. 
- Starting data can be a table with a list of predictors/attributes.

```
package com.oop.ai.com.yesnogame;

import java.util.Scanner;

public class YNGameDriver {


  public static void main(String[] args) {
    BTree tree = new BTree();

    Node root = new Node("Is it a mammal?", "");
    Node node2 = new Node("Is it a dog?", "dog");
    Node node3 = new Node("Is it a bird?", "bird");

    tree.setRoot(root);

    root.setLeft(node2);
    root.setRight(node3);


    Scanner scanner = new Scanner(System.in);
    boolean programIsRunning = true;
    do {
      printMenu();
      String menuChoice = scanner.nextLine();

      switch (menuChoice) {
        case "a":
          startGame(tree, root);
          break;
        case "b":
          programIsRunning = false;
          break;
        default:
          System.out.println("Invalid entry");
          break;
      }

    } while (programIsRunning);

  }

  public static void printMenu() {
    System.out.println("Input a to play the animal guessing game.\n"
        + "Input b to end the program.");
  }

  public static void startGame(BTree tree, Node root) {
//Create Binary Tree
    Scanner scanner = new Scanner(System.in);

    System.out.println("Welcome to 20 Qs for Animals. Think of an animal and answer the questions\n"
        + "with y for yes or n for no.\n");


    boolean questionIsAnswered = false;
    String enteredString;
    do {
      System.out.println(root.getQuestion());

      enteredString = scanner.nextLine().toLowerCase().trim();

      switch (enteredString) {
        case "y":

          tree.setCurrent(root.getLeft());

          questionIsAnswered = true;
          break;
        case "n":


          tree.setCurrent(root.getRight());

          questionIsAnswered = true;
          break;
        default:
          System.out.println("Invalid entry.");
      }

    } while (!questionIsAnswered);

    tree = askNextQuestion(tree);

    System.out.println("Let's play again!");
    startGame(tree, root);

    //tree.setCurrent(Node node);

//    System.out.println("Set the current node to be the root");
//    tree.setCurrent(root.getLeft());
//
//    System.out.println("Display the current node");
//    System.out.println(tree.getCurrent().getQuestion());
//
//    Node currentNode = tree.getCurrent();
//
//    System.out.println("\nDisplay the nodes as tree diagram");

  }

  public static BTree askNextQuestion(BTree tree) {
    Scanner scanner = new Scanner(System.in);

    boolean questionIsAnswered = false;
    String enteredString;
    do {

      Node currentNode = tree.getCurrent();
      System.out.println(currentNode.getQuestion());

      enteredString = scanner.nextLine().toLowerCase().trim();

      switch (enteredString) {
        case "y":
          currentNode.setTrue(true);
          if(currentNode.getLeft() != null) {
            tree.setCurrent(currentNode.getLeft());
            askNextQuestion(tree);
          } else {
            System.out.println("I win!");
          }
          questionIsAnswered = true;
          break;
        case "n":
          currentNode.setTrue(false);

          System.out.println("You win. I give up. What were you thinking of?");
          String userAnswer = scanner.nextLine();
          System.out
              .printf("What question would you ask to tell the difference between a %s and a \n"
                  + "%s?\n", userAnswer, currentNode.getAnimal());
          String userQuestion = scanner.nextLine();

          boolean answerInvalid = false;
          do {
            System.out.printf("What would your answer to this question be for a %s? Yes or No\n",
                userAnswer);
            enteredString = scanner.nextLine().toLowerCase().trim();

            currentNode = tree.getRoot();
            currentNode = currentNode.getLeft();

            if (enteredString.equals("yes")) {

              Node rightNode = new Node(currentNode.getQuestion(), currentNode.getAnimal());
              currentNode.setRight(rightNode);

              currentNode.setQuestion(userQuestion);
              currentNode.setAnimal(null);

              Node leftNode = new Node("Is it a " + userAnswer, userAnswer);
              currentNode.setLeft(leftNode);

            } else if (enteredString.equals("no")) {

              Node leftNode = new Node(currentNode.getQuestion(), currentNode.getAnimal());
              currentNode.setLeft(leftNode);

              currentNode.setQuestion(userQuestion);
              currentNode.setAnimal(null);

              Node rightNode = new Node("Is it a " + userAnswer, userAnswer);
              currentNode.setRight(rightNode);
            } else {
              answerInvalid = true;
              System.out.println("Invalid answer");
            }

          } while (answerInvalid);

          questionIsAnswered = true;
          break;
        default:
          System.out.println("Invalid entry.");
      }

    } while (!questionIsAnswered);

    return tree;
  }

}
```

```
package com.oop.ai.com.yesnogame;

public class Node {

  String question;
  String animal;
  boolean isTrue;
  Node left;
  Node right;


  public Node(String question) {
    this(question,"");
  }

  public Node(String question, String animal) {
    this.question = question;
    this.animal = animal;
    left = null;
    right = null;
  }

  public boolean isTrue() {
    return isTrue;
  }

  public String getAnimal() {
    return animal;
  }

  public void setAnimal(String animal) {
    this.animal = animal;
  }

  public void setTrue(boolean aTrue) {
    isTrue = aTrue;
  }

  public String getQuestion() {
    return question;
  }

  public void setQuestion(String question) {
    this.question = question;
  }

  public void setLeft(Node node) {
    if (left == null)
      left = node;
  }

  public void setRight(Node node) {
    if (right == null)
      right = node;
  }

  public Node getLeft() {
    return left;
  }

  public Node getRight() {
    return right;
  }


  public String print() {
    return this.print("", true, "");
  }

  public String print(String prefix, boolean isTail, String sb) {
    if (right != null) {
      right.print(prefix + (isTail ? "| N  " : "   "), false, sb);
    }
    System.out.println(prefix + (isTail ? "\\-- " : "/-- ") + getQuestion());
    if (left != null) {
      left.print(prefix + (isTail ? "    " : "| Y   "), true, sb);
    }
    return sb;
  }

}
```
```
package com.oop.ai.com.yesnogame;

public class BTree {

  private Node root;
  private Node currentNode;

  public BTree() {
    root = null;
  }

  // Search for a node that contains a particular value
  public boolean search(String question) {
    return search(root,question);
  }

  private boolean search(Node node, String question) {
    if (node.getQuestion().equals(question))
      return true;
    if (node.getLeft() != null)
      if(search(node.getLeft(), question))
        return true;
      if(node.getRight() != null)
        if(search(node.getRight(),question))
          return true;
      return false;
  }


  public Node getRoot() {

    return root;
  }

  public void setRoot(Node root) {
    this.root = root;
  }

  public boolean isEmpty() {
    return root == null;
  }

  public int countNodes() {

    return countNodes(root);
  }

  private int countNodes(Node node) {
    int count = 1;
    if (node == null) {
      return 0;
    } else {
      count += countNodes(node.getLeft());
      count += countNodes(node.getRight());
      return count;
    }
  }

  public void print() {
    root.print();
  }

  public Node getCurrent() {
    return currentNode;
  }

  public void setCurrent(Node node) {
    this.currentNode = node;
  }
}
```
