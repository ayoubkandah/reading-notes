When is Basic Authorization used vs. Bearer Authorization?

basic Authorization depend on username and password wherease bearer bearer Authorization depend on token

What does the JSON Web Token package do?
genereate token depend on username and we can auth account throught it 

What considerations should we make when creating and storing a SECRET?

inside the .env file to be secure


Encryption :- is the method by which information is converted into secret code that hides the information's true meaning
Token :- is a protocol which allows users to verify their identity, and in return receive a unique access token
bearer :- is an HTTP authentication scheme that involves security tokens called bearer tokens
secret :- is a symmetric key that is known by both the sender and the receiver.
JSON Web Token (JWT) is a compact URL-safe means of representing claims to be transferred between two parties.

RBAC

RBAC vs. ABAC vs. ACL
There are some alternatives for/variations of RBAC, including:

Access control lists (ACL) — An ACL is a means of defining access rights by a given user or user group, to a specific object, such as a document.  As a simple example, an ACL could be used to allow users from one department to make changes to a document, while only allowing users from other departments to read the document.

Attribute-based access control (ABAC) — ABAC, sometimes known as policy-based access control, can use a variety of attributes, including user department, time of day, location of access, type of access required, etc. to determine whether a user’s access request should be granted.

Both of these options provide additional granularity of controls beyond the basic concept of RBAC, but can also greatly expand the effort required to create and maintain the necessary permissions.  RBAC arguably offers a more simplified and manageable approach, given that the privileges of a user in a given position are granted with a simple effort, to all others in the same role.  These methods can, however, be used in tandem to increase control.

RBAC implementation 
Hopefully I have convinced you to take a closer look at RBAC. If so, consider the following simplified five-step approach to getting it implemented:

1. Inventory your systems

Figure out what resources you have for which you need to control access, if you don't already have them listed. Examples would include an email system, customer database, contact management system, major folders on a file server, etc. 

2. Analyze your workforce and create roles

You need to group your workforce members into roles with common access needs.  Avoid the temptation to have too many roles defined. Keep them as simple and stratified as possible.

For example, you might have a basic user role, which includes the access any employee would need, such as email and the intranet site. Another role might be a customer service rep, that would have read/write access to the customer database, and a customer database administrator, that would have full control of the customer database. 

3. Assign people to roles

Now that you have a list of roles and their access rights, figure out which role(s) each employee belongs in, and set their access accordingly. 

4. Never make one-off changes

Resist any temptation to make a one-off change for an employee with unusual needs. If you begin doing this, your RBAC system will quickly begin to unravel. Change the roles as required or add new ones when really necessary. 

5. Audit

Periodically review your roles, the employees assigned to them, and the access permitted for each. If you discover, for example, that a role has unnecessary access to a particular system, change the role and adjust the access level for all employees in that role. 

As an example, many healthcare organizations, given the need for regulatory compliance in controlling access to medical records, use RBAC to define exactly what access to medical records each type of clinician may need.  While a doctor might have almost unlimited access to the records of patients he/she manages, a receptionist might be limited to basic contact information needed to manage appointments.  Given the large number of staff members in well stratified roles, RBAC is an efficient way to control record access in compliance with HIPAA, and other regulations.






