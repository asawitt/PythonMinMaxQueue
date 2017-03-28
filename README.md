# PythonMinMaxQueue
MinMaxQueue DS for HackerRank challenges

## Notes
-This code repeats the code from my Python MinMaxStack: https://github.com/asawitt/PythonMinMaxStack because HackerRank only allows access to modules within the Python Standard Library. If you're using this code elsewhere, and especially if you're also using my PythonStack, you should consider deleting the Stack portion in MinMaxStack.py and importing it as a module in order to avoid unnecessary duplication. 

-This will also be the end of my Python Data-Structures as I've come across several questions on HackerRank which Python is too slow to solve within the requisit time-limit

## Installation
-Fastest would be to copy-paste the contents of MinMaxQueue.py into your code 

-Or you could download MinMaxQueue.py and throw it in your project directory. Use "from DisjointSet import *" to use it in your code

-You could clone https://github.com/asawitt/PythonMinMaxQueue/ , move MinMaxQueue.py to your project directory, then use the above import statement if you really want to. Don't. 

## Usage
### To Create a min stack (or max stack) pass in the desired function:
min_queue = MinMaxQueue(min) 

max_queue = MinMaxQueue(max)
### Push O(1):
min_Queue.push(value)
### Peek O(1):
-Returns the value at the top of the stack:

min_queue.peek()

### Pop amortized O(1):
-Remove the item at the front of the Stack and return the value

min_queue.pop()

### Getting the size O(1)
-Returns the number of elements in the Stack

min_queue.getSize()

### Check if the Queue is empty O(1)
-Returns True if the Queue is empty, False otherwise

min_queue.isEmpty()

### Get the current min (or max) in the Queue O(1):
min_queue.query() #returns the min value in the queue (or max, depending on the function passed in on initialization)

## License
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


