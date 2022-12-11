# Idea: Issue reporting
A way for your users on a website or application to report issues and give feedback.
To be able to easily implement a reporting function on any website, there should be a library with a minimalistic UI that can hook into any button.
All API endpoints should be well documented and can be used if a custom integration is needed.

Privacy is always important to keep in mind and we should not require any unncessary information to be submitted by the user. There should also not be any hidden information sent that the user is not aware of.

## Definitions
* **Users**, a person using your website or application.
* **Administrator**, the person using the library and implementing it on there website or application.
* **Submit**, to send an issue by a user.

## Features
- [ ] Users can submit a short summary of the issue in text form.
- [ ] Users can include a picture of the current page.
- [ ] Administrators can see all user submitted feedback in a dashboard.
- [ ] Users can preview the information before it is being sent. This should include all hidden information as well, such as IP, device information etc.
- [ ] Users can submit issues without being authenticated. However if a user is authenticated the users email/identifier can be sent along with the issue.
  - [ ] Users that are authenticated can select to submit a issue anonymously.

## Useful links and resources
* [Feedback Fish](https://feedback.fish/)
* [react-feedback-widget](https://github.com/servoice/react-feedback-widget)
* [react_feedback_widget](https://github.com/BinaryLeo/react_feedback_widget)