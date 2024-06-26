# DAY-11

Search Binay Tree

Problem Statement

Given the root of a BST and an integer val.
Find the node in the BST that the node's value equals val and return the subtree rooted with that node. If such a node does not exist, return null.

Solution

Using recurssion go root->left if val is less than root->val else right until val is found 
