# pyramide_semaine_0
puts "Salut, bienvenue dans ma super pyramide ! Combien d'étages veux-tu ?"
print "> "
num = gets.to_i
fois = 1

puts "voici la pyramide :"
while fois <= num
	puts ("#" * fois).rjust(num)
	fois += 1
end
