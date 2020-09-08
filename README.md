# digital-house-ios-interview-forex
Interview project template - FOREX Calculator

# UI & UX

## Main View
### Presentation
- List of currency pairs
- List is empty when starting the app for the first time, or if user hasn’t added any currency pairs.
- New currency pairs are added to the list

### Interaction
- User can add a new currency pair (see point 3. Add new currency)
- User can tap on one of the currency pairs 
- App navigates to detail view

## Detail View
### Presentation
- Simple presentation of the currency pair-values against each other

### Interaction
- User can delete the currency pair
- User can dismiss the detail view

## Add new currency
### Where, (e.g)
- Modal
- In the detail view (point 2. Detail View)
- Main screen, e.g as a footer

### How
- View allows numerical input for the value of
  - Main Currency
  - Secondary Currency

- View allows selection of 
  - Main Currency (e.g GBP)
  - Secondary Currency (e.g EUR)

- Changing value of one of the currencies automatically changes the value of the other currency
  - Use a closure/lambda to simulate API call for calculated  
    - Returned value - static is enough, e.g 12.34

## General Information
- On start of app, app retrieves a defined list of currencies
  - API call can be simulated with a closure/lambda

## Key Words
Currency - USD / GBP / EUR / etc
Currency pairs - USD : GBP / GBP : USD / EUR : GBP / etc
Value - 100 / 100.2 / 100.20 / 100.03 / etc 

# FOR INTERVIEWER ONLY

What patterns/ways are used to communicate between views

What patterns/ways are used to separate models, views, logic

What patterns/ways are used for some kind of reactiveness 

Lead a discussion about networking → [persistence] → in-memory data

Notice if generics are used / mentioned

Protocol oriented + generics?

Lead discussions about possible packaging and versioning

Keep an open mind regarding techniques and help the dev reach the goal the way they feel most comfortable with

Allow candidate to search “on-the-line” for whatever needed
