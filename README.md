# TEST
This is test for github
class ListNode {
private: 
	int data;
	ListNode *next;
public:
	ListNode() :data(0), next(0) {};
	ListNode(int a) :data(a), next(0) {};
	friend class LinkedList;
};

class LinkedList {
private:
	ListNode *first;
public:
	LinkedList() :first(0) {};
	void PrintList();
	void Push_front(int);
	void Push_back(int);
	void Delete(int);
	void Clear();
	void Reverse();
};
