preOrderTraversal(node)
       {
            if( noe != NULL )
            {
                access(node->value);
                preOrderTraversal(node->left);
                preOrderTraversal(node->right);
            }
        }
