# Rock-Paper-Scissors

A simple Game 

mine=(rand() * 10).to_i

#Your choice
puts 'Enter a number between zero and 9:'
yours= gets.chomp.to_i
puts


 #Computer choice 

 if mine<3
puts 'My choice is Rock'
mine1="rock"

 elsif
mine<6
    puts 'My choice is Paper'
	mine1="paper"
 else
mine<9 
    puts 'My choice is Scissors' 
	mine1="scissors"
 end


if yours<3
puts 'Your choice is Rock'
yours1="rock"

elsif
yours<6
    puts 'Your choice is Paper'
	yours1="paper"
else
yours<9
    puts 'Your choice is Scissors'
	yours1="scissors"
 end

#tie
if mine1 == yours1 
puts "It's a tie! Try again."
end


if mine1 == "rock" && yours1 == "paper" 
puts "You win!"
elsif mine1 == "rock" && yours1 == "scissors"
puts "You Lose"
end


if mine1 == "paper" && yours1 == "rock" 
puts "you lose"
elsif mine1=="paper"&&yours1=="scissors"
puts "You win!"
end


if mine1=="scissors" &&  yours1 == "rock"
puts "You win!"
elsif mine1="scissors" && yours1 == "paper" 
puts "you lose"
end
