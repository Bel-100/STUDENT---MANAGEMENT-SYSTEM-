   // Student class example
   class Student {
   public:
       string indexNumber;
       string name;
       
       Student(string idx, string n) : indexNumber(idx), name(n) {}
       void display() {
           cout << "Index: " << indexNumber << ", Name: " << name << endl;
       }
   };
   

