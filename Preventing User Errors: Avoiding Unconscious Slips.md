Origin article: http://www.nngroup.com/articles/slips/


Preventing User Errors: Avoiding Unconscious Slips

Summary: Users are often distracted from the task at hand, so prevent unconscious errors by offering suggestions, utilizing constraints, and being flexible.

One of the 10 Usability Heuristics advises that it’s important to communicate errors to users gracefully, actionably, and clearly. However, it’s even better to prevent users from making errors in the first place

A crucial point in discussing user errors is where to assign the blame for the error. The term “user error” implies that the user is at fault for having done something wrong. Not so. The designer is at fault for making it too easy for the user to commit the error. Therefore, the solution to user errors is not to scold users, to ask them to try harder, or to give them more extensive training. The answer is to redesign the system to be less error prone.
Two Types of User Errors

Before discussing how to prevent errors, it’s important to note that there are two types of errors that users make: slips and mistakes. (Both are discussed in much greater detail in Don Norman’s book The Design of Everyday Things.)

    Slips occur when users intend to perform one action, but end up doing another (often similar) action. For example, typing an “i” instead of an “o” counts as a slip; accidentally putting liquid hand soap on one’s toothbrush instead of toothpaste is also a slip. Slips are typically made when users are on autopilot, and when they do not fully devote their attention resources to the task at hand.
    Mistakes are made when users have goals that are inappropriate for the current problem or task; even if they take the right steps to complete their goals, the steps will result in an error. For example, if I misunderstood the meaning of the oil-pressure warning light in my car, and thought it was the tire-pressure monitor, no matter how carefully I added air to my tires, it would not fix the issue with my oil pressure. This would be a mistake, since the goal that I was attempting to accomplish was inappropriate for the situation, even though I made no errors in executing my plan. Mistakes are conscious errors, and often (though not exclusively) arise when a user has incomplete or incorrect information about the task, and develops a mental model that doesn’t match how the interface actually works.

This article focuses on preventing unconscious slip-type errors, and a second article will address mistakes.
General Guidelines for Preventing Slips

Slips often happen when users are quite familiar with the goal that they seek to achieve and with the procedure for accomplishing that goal, but accidentally they take the wrong step when trying to achieve it. Often, when executing tasks that are well practiced, we tend to allocate fewer attentional resources, and, as a result, we can “slip” and perform the wrong action. Thus, ironically, slip-type mistakes often are made by expert users who are very familiar with the process at hand; unlike new users who are still learning how to use the system, experts feel that they have mastered the task and need to pay less attention to its actual completion.

Strategies for preventing slips are centered around gently guiding users so that they stay on the right path and have fewer chances of slipping. Assist users by providing the needed level of precision, and encourage users to check for errors.
Include Helpful Constraints

While it’s not always a good idea to limit users’ choices, in cases where there are clear rules that define acceptable options, it can be a good strategy to constrain the types of input users can make.

For example, booking a flight typically involves selecting the dates of travel, and there are a few rules that govern which dates are acceptable. One of the major rules is that a return flight cannot happen before a departure. If users aren’t limited in the dates they can choose, they may slip and accidentally select a set of dates for their flight that don’t follow the rules. A helpful constraint here will force users to pick a date range that fits.
Southwest Airlines calendar picker interface
Southwest’s calendar widget for picking flight dates uses helpful constraints to prevent users from accidentally setting a nonsensical date range. Even if users attempt to set the return date before the departure date, this widget forces them to pick a departure date first. In addition, it subtly uses color to provide context about which date is about to be changed (in this case, blue for departure), which helps users see which field they are selecting (instead of having to keep that information in their working memory).
Offer Suggestions

Similarly to how constraints guide users toward the correct use of an interface, suggestions can preempt many slips before the user has the opportunity to make them. On websites that offer thousands of products, search is an effective way of helping users find their proverbial needle in a haystack. However, typing can be inaccurate, especially on touchscreens where there isn’t any tactile (also known as haptic) feedback. While you cannot prevent a user from making typos (which are slip-type errors), you can preempt typos from turning into problems by offering contextual suggestions while the user types.

Offering search suggestions has also the benefit of supporting recognition over recall in those situations when the users misremember the name of the product or content they’re looking for.
Amazon predictive search suggestions
Remembering how to spell Etymotic Research is difficult for users searching for high-quality headphones, and typing is likely to be low accuracy as well. Amazon’s clickable search suggestions enable users to type less, thereby making fewer slips or mistakes that would produce no results.
Choose Good Defaults

Another type of helpful suggestion is the good default. Especially when users have to perform repetitive actions, or in situations where they need to use precision, start by offering reasonable defaults that are likely to fit their real-world goals, and then allow them to refine their choices. For example, in a reminder app, a few typical preset options, such as Tomorrow, Next Week, In one Hour, and so on, can prevent typos in dates or times; a reminder to take dinner out of the oven that comes a day late is definitely not helpful.
Google Inbox iOS app snooze function
Google’s Inbox app for iOS allows you to “snooze” an email until a later time. The default options are sensible and prevent typing errors for common choices.

Good defaults also help reduce mistakes, because they teach users about reasonable values for the question at hand. They help users better understand the question and sometimes make them realize that they are on the wrong track.
Use Forgiving Formatting

Some tasks really do require users to type very detailed or precise information, but forcing people to provide this information in a very specific format can be at odds with good usability practices: If you are asking users to input numerical information into a form, be flexible, and format that information in a way that is easily scannable (by humans, not machines) in order to prevent mistakes.

For example, on account registration forms, there’s often a field requesting a phone number. However, many users have challenges scanning a long row of digits that isn’t broken up with spaces or punctuation, and are less likely to spot mistakes. This is why in the US (and in many other countries) we write phone numbers in the format “(777) 555-1212” —this format groups digits into smaller chunks that are easier to scan.

While your website’s database might not allow nonnumeric characters to be stored in a phone number, you surely want your users to notice typos when they enter their phone number. One solution is to let users type in a way that’s natural to them, rather than forcing them to use the format that your application expects. Do some behind-the-scenes data scrubbing to remove parentheses or other characters that users may type, rather than frustrating them with an inflexible format.

An even better solution is to format the users’ input as they type —like Uber’s website does during account creation. Once you begin typing, the form adds the spaces, parentheses, and hyphens where they normally go, and also ignores additional nonnumeric characters (which acts as a type of helpful constraint, preventing users from adding unnecessary extra parentheses, for example). This helps the user understand what characters they should type, and does the work of reformatting, making it much easier for users to read and double-check their own work.
Uber.com's signup form
Uber.com automatically displays the phone number in the desired format as users type, so that they can more easily scan their work to confirm that it’s correct.
Summary

Slips are common errors that happen when users do not pay full attention to a task or have small memory lapses. Preventing errors of this type is largely a matter of reducing burdens on users and guiding them when precision is required.

In the next article in this series, we will explore strategies to prevent users from making mistakes, where their goals have been erroneously formed from a poor model of the interface. In addition, we will examine strategies that apply well to preventing both slips and mistakes.
