# Acronym
Python Acronym

input_text = input("Enter the text: ")
split_the_text = input_text.split()
output_text = " "
for i in split_the_text:
    output_text = output_text + str(i[0]).upper()
print(output_text)
