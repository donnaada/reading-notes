# 🗒️ Class 05

`append` = adds to the end of the list

`insert` = adds to the head of the list

`traversal` = moving through the list

***sample prototype method for traversal***

``` javascript

traversal(){
  let current = this.head;
  
  while (current){
    console.log('current>>',current.value);
    current = current.next;
    console.log('next>>',current.next);
  }
}

```
