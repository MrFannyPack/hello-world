# hello-world
Learning to use github
I am learning this stuff very quckly and I will be a great developer soon!
This will not have any code but it is good practice


Code for putting an array in reverse order

def alphabetize(arr, rev = false)
  arr.sort!
  if rev == true
    arr.reverse!
  else
  	arr
  end
end

numbers = [3, 5, 1, 6]

puts alphabetize(numbers)
