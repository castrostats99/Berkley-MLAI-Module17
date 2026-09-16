# Berkley-MLAI-Module17
Code for assignment module 17 due 9-3-2026
Based on the F score, the model is the Decision Tree with a max depth of three.
Based on the Decision Tree the first stage looks at nr.employed: number of employees - quarterly indicator (numeric) and shows that a number over 5,087.65 leads to higher duration calls. Longer call duration is strongly linked to term deposit subscriptions to a certain point of around 834.5 seconds. A low consumer price index leads to fewer subscriptions. pdays: number of days that passed after the client was last contacted from a previous campaign (numeric; 999 means the client was not previously contacted); values greater than 7.5 lead to more subscriptions. Overall, the biggest driver of sign-ups is the economy; based on the number of employees, having fewer than 5,087 employees drives most subscriptions.

Follow-up: The bank should try calling customers to offer subscriptions when the economy is declining, since they seem more likely to sign up. Also, employees should be trained not to call people contacted within the last week and to spend between 172 and 800 seconds per call.
