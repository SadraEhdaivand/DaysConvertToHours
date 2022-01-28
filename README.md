# DaysConvertToHours

calculation_to_units = 24
name_of_unit = "hours"

def days_of_units(num_of_days):
    
    if num_of_days > 0 :    
            return(f"{num_of_days} days are {num_of_days * calculation_to_units} {name_of_unit}")

    else:
             return("you enter negative number dummy😐")

user_input = input("hey user, enter a number of days and i convert that to hours :😍")
user_input_number = int(user_input)

calculate_value = days_of_units(user_input_number)
print(calculate_value)


    
    








