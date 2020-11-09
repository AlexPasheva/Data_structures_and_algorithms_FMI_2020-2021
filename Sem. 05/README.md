����:
**�������� � ���������� �� ���� � ���� ������.**

*1 �������: pushBack + popBack*
|                  | pushBack | popBack |   |
|------------------|----------|---------|---|
| Vector           |  O(1)*   |  O(1)*  |   |
| SinglyLinkedList |  O(1)    |  O(n)   |   |
| DoublyLinkedList |  O(1)    |  O(1)   |   |


*2 �������: pushFront + popFront*
|                  | pushFront | popFront |   |
|------------------|----------|-----------|---|
| Vector           |  O(n)    |  O(n)     |   |
| SinglyLinkedList |  O(1)    |  O(1)     |   |
| DoublyLinkedList |  O(1)    |  O(1)     |   |

������:
**�������� � ���������� �� ����� �������������� ������**

*1 �������: pushBack + popFront*

|                  | pushBack | popFront |   |
|------------------|----------|----------|---|
| Vector           |  O(1)*   |  O(n)    |   |
| SinglyLinkedList |  O(1)    |  O(1)    |   |
| DoublyLinkedList |  O(1)    |  O(1)    |   |

*2 �������: pushFront + popBack *

|                  | pushFront | popBack |   |
|------------------|----------|----------|---|
| Vector           |  O(n)    |  O(1)*   |   |
| SinglyLinkedList |  O(1)    |  O(n)    |   |
| DoublyLinkedList |  O(1)    |  O(1)    |   |

3 �������: ���������� ������