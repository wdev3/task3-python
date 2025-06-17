product_question = input("Which products do you want to buy?\n").split(",")
name_question = input("What is your name?\n")
city_question = input("Enter your city name\n")
payment_question = input("Enter the payment method\n")


def user_order_registration(*products, **data):
    print("Order summary")
    print(f"Products:\n {products}")
    print("Customer:")
    for key, value in data.items():
        print(key, "=", value)
    print(len(products))


user_order_registration(product_question, name=name_question, city=city_question, payment=payment_question)
