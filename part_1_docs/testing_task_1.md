### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

#  add a colon added at end of "else", also needs to be double equal sign:
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else:
      return False
   

# There needs to be a comma after card1 and there's a typo "dif" should be "def", "if" needs to be indented and "else indented"
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

# "def" needs to be in line with the previous two "defs" above, "total" shouldn't be on line 37
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
