print("Welcome to th secret auction program.")

should_continue=True
bidders_details={}

while should_continue:
    name=input("what is your name? : ")
    bid=input("What's your bid? : $")
    Yorn=input("Are there any other bidders? Type 'yes' or 'no'. \n")
    print("\n  "*100)

    if Yorn!="yes":
        should_continue=False

    bidders_details[name]=bid

value=0
winner=""

for bidder in bidders_details:
    if int(bidders_details[bidder])>value:
        value=int(bidders_details[bidder])
        winner=bidder

print("\n"*100)
print(f"The winner is {winner} with a bid of ${value}")
