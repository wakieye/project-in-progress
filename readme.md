new_patient = False


critical_level = False
good_condition = True
mobile = True
recover=True
conscious = False
stable= False
satisfy= True
survive= True

update_details = False
if new_patient:
    print("welcome to maryland hospital")
    if critical_level:
        print("the following instructions should be followed to the latter")
        if critical_level and not mobile:
            icu = input('icu room number: ')
            print("move the patient to icu room  " + icu)
            if recover:
                if recover and conscious:
                    nurse_name = input("please enter nurse's name")
                    emergency_contact = input('patient emergency contact: ')
                    print("nurse " + nurse_name + "ask patient for their emergency contact's number")
                    print("nurse " + nurse_name + " call " + emergency_contact)
                elif recover and not conscious:
                    nurse_name = input("please enter nurse's name")

                    print("doctor please assign a nurse to look after the patient")
                    print("nurse assigned" + nurse_name)
                    print(nurse_name + "  your have been assigned patient ")
            else:
                print("nurse record time of death and call the mortician to")
                print("move body to the morgue")

                print("contact the national record center and inform them of /n the anonymous patient  who just passed away")
        elif critical_level and mobile:
            icu = input('icu room number: ')
            print("move the patient to icu room  " + icu)
            if recover and not stable:
                nurse_name = input("please enter nurse's name")
                name = input(' patient name:')
                birth_year = input('birth year ')
                age = 2020 - int(birth_year)
                blood_type = input("please state your blood type")
                weight = input(' patient weight: ')
                patient_home_address = input(' patient homes address:')
                emergency_contact = input('patient emergency contact: ')
                contact = input('patient contact: ')
                print("doctor please assign a nurse to look after the patient")
                print("nurse assigned" + nurse_name)
                print(nurse_name + "  your have been assigned patient  " )
                print(nurse_name + " ask patient for their information")
                print(name)

                print("birth year: " + birth_year)
                print("blood type: " + blood_type)
                print("weight: " + weight)
                print("home adress: " + patient_home_address)
                print("emergency contact: " + emergency_contact)
                print("contact: " + contact)
            elif recover and stable:
                nurse_name = input("please enter nurse's name")
                name = input(' patient name:')
                birth_year = input('birth year ')
                age = 2020 - int(birth_year)
                blood_type = input("please state your blood type")
                weight = input(' patient weight: ')
                patient_home_address = input(' patient homes address:')
                emergency_contact = input('patient emergency contact: ')
                contact = input('patient contact: ')

                print(name + " please enter your details below")
                print("birth year: " + birth_year)
                print("blood type: " + blood_type)
                print("weight: " + weight)
                print("home adress: " + patient_home_address)
                print("emergency contact: " + emergency_contact)
                print("contact: " + contact)
                print("nurse" + nurse_name + "please handle discharge forms for " + name)
    elif good_condition:
        print("patient should fill their details in the form below while waiting in the recieption line")
        name = input(' patient name:')
        birth_year = input('birth year ')
        age = 2020 - int(birth_year)
        blood_type = input("please state your blood type")
        weight = input(' patient weight: ')
        patient_home_address = input(' patient homes address:')
        emergency_contact = input('patient emergency contact: ')
        contact = input('patient contact: ')
        print("name" + name)
        print("birth year: " + birth_year)
        print("blood type: " + blood_type)
        print("weight: " + weight)
        print("home adress: " + patient_home_address)
        print("emergency contact: " + emergency_contact)
        print("contact: " + contact)
        if recover or stable:
            name = input(' patient name:')
            print(name + "were the services satisfying")
            if satisfy:
                doctor_name = input("enter doctor's name")
                nurse_name = input("please enter nurse's name")
                print("enter the doctor's name and nurse's  in the slots below")
                print("nurse name" + nurse_name)
                print("doctor's name" + doctor_name)
                print("welcome to santa lucia hospital " + name + "incase of any complications later /n call 079887787767")
                print("have a nice day, the nurse" + nurse_name + "will discharge you")
            else:
                doctor_name = input("enter doctor's name")
                nurse_name = input("please enter nurse's name")
                print("enter the doctor's name and nurse's  in the slots below")
                print("nurse name" + nurse_name)
                print("doctor's name" + doctor_name)
                print("we will look into the issue")
                print("welcome to santa lucia hospital " + name + "incase of any complications later /n call 079887787767")
                print("have a nice day, the nurse" + nurse_name + "will discharge you")
        else:
            print("nurse record time of death and call the mortician to")
            print("move body to the morgue")

            print("contact the national record center and inform them of /n the anonymous patient  who just passed away")
else:
    if critical_level:
        print("the following instructions should be followed to the latter")
        if critical_level and not mobile:
            icu = input('icu room number: ')
            print("move the patient to icu room  " + icu)
            if recover:
                if recover and conscious:
                    nurse_name = input("please enter nurse's name")
                    emergency_contact = input('patient emergency contact: ')
                    print("nurse " + nurse_name + "ask patient for their emergency contact's number")
                    print("nurse " + nurse_name + " call " + emergency_contact)
                elif recover and not conscious:
                    nurse_name = input("please enter nurse's name")

                    print("doctor please assign a nurse to look after the patient")
                    print("nurse assigned" + nurse_name)
                    print(nurse_name + "  your have been assigned patient ")
            else:
                print("nurse record time of death and call the mortician to")
                print("move body to the morgue")

                print(
                    "contact the national record center and inform them of /n the anonymous patient  who just passed away")
        elif critical_level and mobile:
            icu = input('icu room number: ')
            print("move the patient to icu room  " + icu)
            if recover and not stable:
                nurse_name = input("please enter nurse's name")
                name = input(' patient name:')
                birth_year = input('birth year ')
                age = 2020 - int(birth_year)
                blood_type = input("please state your blood type")
                weight = input(' patient weight: ')
                patient_home_address = input(' patient homes address:')
                emergency_contact = input('patient emergency contact: ')
                contact = input('patient contact: ')
                print("doctor please assign a nurse to look after the patient")
                print("nurse assigned" + nurse_name)
                print(nurse_name + "  your have been assigned patient  ")
                print(nurse_name + " ask patient for their information")
                print(name)

                print("birth year: " + birth_year)
                print("blood type: " + blood_type)
                print("weight: " + weight)
                print("home adress: " + patient_home_address)
                print("emergency contact: " + emergency_contact)
                print("contact: " + contact)
            elif recover and stable:
                nurse_name = input("please enter nurse's name")
                name = input(' patient name:')
                birth_year = input('birth year ')
                age = 2020 - int(birth_year)
                blood_type = input("please state your blood type")
                weight = input(' patient weight: ')
                patient_home_address = input(' patient homes address:')
                emergency_contact = input('patient emergency contact: ')
                contact = input('patient contact: ')

                print(name + " please enter your details below")
                print("birth year: " + birth_year)
                print("blood type: " + blood_type)
                print("weight: " + weight)
                print("home adress: " + patient_home_address)
                print("emergency contact: " + emergency_contact)
                print("contact: " + contact)
                print("nurse" + nurse_name + "please handle discharge forms for " + name)
    elif good_condition:
        print("patient should fill their details in the form below while waiting in the recieption line")
        name = input(' patient name:')
        birth_year = input('birth year ')
        age = 2020 - int(birth_year)
        blood_type = input("please state your blood type")
        weight = input(' patient weight: ')
        patient_home_address = input(' patient homes address:')
        emergency_contact = input('patient emergency contact: ')
        contact = input('patient contact: ')
        print("name" + name)
        print("birth year: " + birth_year)
        print("blood type: " + blood_type)
        print("weight: " + weight)
        print("home adress: " + patient_home_address)
        print("emergency contact: " + emergency_contact)
        print("contact: " + contact)
        if recover or stable:
            name = input(' patient name:')
            print(name + "were the services satisfying")
            if satisfy:
                doctor_name = input("enter doctor's name")
                nurse_name = input("please enter nurse's name")
                print("enter the doctor's name and nurse's  in the slots below")
                print("nurse name" + nurse_name)
                print("doctor's name" + doctor_name)
                print(
                    "welcome to santa lucia hospital " + name + "incase of any complications later /n call 079887787767")
                print("have a nice day, the nurse" + nurse_name + "will discharge you")
            else:
                doctor_name = input("enter doctor's name")
                nurse_name = input("please enter nurse's name")
                print("enter the doctor's name and nurse's  in the slots below")
                print("nurse name" + nurse_name)
                print("doctor's name" + doctor_name)
                print("we will look into the issue")
                print(
                    "welcome to santa lucia hospital " + name + "incase of any complications later /n call 079887787767")
                print("have a nice day, the nurse" + nurse_name + "will discharge you")
        else:
            print("nurse record time of death and call the mortician to")
            print("move body to the morgue")

            print("contact the national record center and inform them of /n the anonymous patient  who just passed away")













