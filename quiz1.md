1. 可以表示的精確不同，Fixnum (整數)不能表示小數點之後的數值，Float (浮點數)就可以表示

2. 使用'+'的方式比內插還要耗費記憶體

3. array : 使用位置index取得成員
   hash  : 建立時可以賦予每個成員key值，可以使用key值取得成員

4. 
  ```ruby
  [1, "a string", 3.14, [1,2,3,4]].select {|x| !x.is_a? String }
  ```
  
5. arr.map! {|x| x + 2}

6. [1, 2, 3, 3]
   uniq    複製一個新的陣列回傳
   uniq!   直接改變原本的陣列，並回傳該陣列

7. 
  ```ruby
  rand(1..10)
  [1,2,3,4,5,6,7,8,9].sample
  ```

8. true

9.  binding.pry是ruby的一個gem，使用gem安裝好之後，在ruby的程式碼中下指令'binding.pry'，當ruby執行到'binding.pry'這行程式碼時，執行程序會停在當下，並且可以顯示當下訊息在console上

10. 
  ```ruby
  var = 5
  return var >= 5 ? "var is greater than or equal to 5" : "var is less than 5"
  ```

11. 
  ```ruby
  { :name => "Tom" }
  { name: "Mary" }
  ```