Here's the Ruby code I used to solve it:


def ordinal(numeral)
  lop = numeral % 10
 if lop == 1 && numeral != 11
   puts "That's the #{numeral}st."
 elsif lop == 2 && numeral != 12
   puts "That's the #{numeral}nd."
 elsif lop == 3 && numeral != 13
   puts "That's the #{numeral}rd."
 else 
   puts "That's the #{numeral}th."
 end
end
puts "Enter a number:"
number = gets.chomp.to_i
call = ordinal(number)
