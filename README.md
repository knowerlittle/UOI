:moneybag: UOI :moneybag:
======
A Web App that creates IOUs using spam tactics as payment reminders. [View Site](https://uoi.herokuapp.com/)

##Installation
**Technologies used:**
<br>
`Ruby on Rails, Materalize CSS, PostgreSQL, Heroku`
</br>
**Testing Frameworks:**
<br>
`RSpec / Capybara`

1. Clone this repository
2. Run `bundle install` to install Gemfiles
3. Run `rake db:create` to create databases
4. Run `rake db:migrate` to create database tables
5. Run `rspec` to make sure all tests are passing! 
5. Run `rails s` to start server
6. In a Web Browser open up `localhost:3000`
7. Start spamming your friends with IOUs!

## How it works
- Users sign up to create and keep track of IOUs 
- A new IOU is created by clicking on the `create IOU` Icon at the bottom right of the screen and filling in the form
- Once the IOU is created an initial e-mail is sent to the contact provided
- The e-mail sent out lists the name of the sender, the event, and the amount of money owed
- Once the recipiant accepts the IOU, **the spamming happens**
- E-mails are sent out to get payment
- The spamming will only stop once the recipiant clicks the link to pay amount owed
- IOUs change colour according to their different states: Pending / Accepted / Paid
- Emails are sent from the e-mail address `pmnbapp@gmail.com`

Authors
-------
 - [Fergus Orbach](https://github.com/gerauf)
 - [Maggie Allen](https://github.com/pixelandpage)
 - [Lucy Clarke](https://github.com/llcclarke)
 - [Noah Pollock](https//github.com/knowerlittle)

License
-------
:hatching_chick: Free as a bird - 2016 :hatched_chick:
