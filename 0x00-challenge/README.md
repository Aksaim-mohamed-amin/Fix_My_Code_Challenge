# 0x00. Fix My Code

Welcome to the "0x00. Fix My Code" repository! This repository contains challenges where I'll be tasked with fixing code that has bugs, errors, or inefficiencies. The challenges are designed to help improve my debugging skills, understand common programming pitfalls, and enhance your problem-solving abilities.

## About

In this repository, you'll find various programming challenges with code that needs fixing. Each challenge comes with a set of instructions and a codebase containing bugs or issues that need to be addressed. Your goal is to identify and fix these issues to ensure that the code behaves as expected and produces the desired output.

- [x] 0. FizzBuzz :
	The problem in the code was that the order of the 'if' statements is incorrect, causing the "FizzBuzz" condition to never be reached.

- [x] 1. Print square :
	The problem in the code was with the `parseInt()` function. Using the value `16` as the second argument caused it to interpret the number in base 16 instead of base 10, leading to incorrect conversion.

- [x] 2. Sort :
	The problem in the code was with the `insert()` method, as it is not inserting the element at the correct position.

- [x] 3. User password :
	The issues in the code were as follows:
	-  Typo mistake in the setter method for the password. It should assign the value to `self.__password` instead of `self._password`.
	-  In the `is_valid_password()` method, in the MD5 hashing, it should use `lower()` instead of `upper()` to match the method in the password setter.

- [x] 4. Double linked list :
The problem with this code is in the `else` block of the `delete_dnodeint_at_index()` function. When deleting a node that is not at the beginning of the list (i.e., when `index` is not 0), the code is not correctly linking the previous node to the next node. Specifically, it's not updating the `next` pointer of the previous node to point to the next node after the one being deleted.
