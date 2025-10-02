# comp163-assignment-5-reredo-
Loop mastery assignment
# comp163-assignment-5
Loop mastery assignment
print("=== Challenge 1: Collatz Conjecture ===")
current_number = int(input("Enter starting number: "))
step_count = 0 
print("Sequence:", end=" ") #keeps everything on the same line 
while current_number != 1:
    print(current_number, end=" ")
    if current_number % 2 == 0: #If multiple of 2 aka even nummber 
        current_number = current_number // 2
    else:current_number = current_number * 3 + 1     
    step_count += 1 
print(1)
print("Steps:", step_count)
