#include <iostream>
using namespace std;

// Definition of a node in the binary search tree
struct TreeNode {
    int val;
    TreeNode* left;
    TreeNode* right;
    TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
};

class BST {
private:
    TreeNode* root;

    // Recursive helper function to insert a value into the tree
    TreeNode* insert(TreeNode* node, int val) {
        if (node == nullptr) {
            return new TreeNode(val);
        }
        if (val < node->val) {
            node->left = insert(node->left, val);
        } else {
            node->right = insert(node->right, val);
        }
        return node;
    }

    // Recursive helper function to search for a value in the tree
    bool search(TreeNode* node, int val) {
        if (node == nullptr) {
            return false;
        }
        if (val == node->val) {
            return true;
        } else if (val < node->val) {
            return search(node->left, val);
        } else {
            return search(node->right, val);
        }
    }

public:
    // Constructor
    BST() : root(nullptr) {}

    // Public function to insert a value into the tree
    void insert(int val) {
        root = insert(root, val);
    }

    // Public function to search for a value in the tree
    bool search(int val) {
        return search(root, val);
    }
};

int main() {
    BST bst;
    bst.insert(5);
    bst.insert(3);
    bst.insert(7);
    bst.insert(1);
    bst.insert(4);

    cout << "Searching for 3: " << (bst.search(3) ? "Found" : "Not Found") << endl;
    cout << "Searching for 6: " << (bst.search(6) ? "Found" : "Not Found") << endl;

    return 0;
}
