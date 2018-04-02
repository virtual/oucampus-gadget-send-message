# Send Message gadget
Simple Send Message gadget created for OUTC18

## Set up

- Put `lib` and `send_message` folders into `/_resources/gadgets/` folder and publish
- Copy published link of `send_message` directory
- Go to Setup > Gadgets; add new Gadget using this directory link (should not include `index.html`)
- Gadget should now be available on CMS page sidebars; hard-refresh if not showing

## Use

![Send Message Gadget][thumb]

- Select a user
- Write a message
- Click send
- User receives an email at the email associated with their OU Campus account
- Email includes link of page 

## Issues

- Page URL does not update when moving about OU Campus
- Update user selection to include the users associated for current directory only

[thumb]: https://github.com/virtual/oucampus-gadget-send-message/thumbnail.png "Screenshot of message gadget"
