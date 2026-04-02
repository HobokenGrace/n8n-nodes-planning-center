---
name: pco-api-people
description: Planning Center People helps you manage contact data, membership info, and everything you need to know about your people with confidence.. Use when working with the Planning Center People or when the user needs to interact with this API.
metadata:
  api-version: "2025-11-10"
  openapi-version: "3.1.1"
  contact: "support@planningcenter.com"
---

# Planning Center People

Planning Center People helps you manage contact data, membership info, and everything you need to know about your people with confidence.

## How to Use This Skill

This API documentation is split into multiple files for on-demand loading.

**Directory structure:**
```
references/
├── resources/      # 36 resource index files
├── operations/     # 502 operation detail files
└── schemas/        # 82 schema groups, 630 schema files
```

**Navigation flow:**
1. Find the resource you need in the list below
2. Read `references/resources/<resource>.md` to see available operations
3. Read `references/operations/<operation>.md` for full details
4. If an operation references a schema, read `references/schemas/<prefix>/<schema>.md`

## Base URL

- `https://api.planningcenteronline.com/people/v2`

## Authentication

Supported methods: **oauth2**, **personal_access_token**. See `references/authentication.md` for details.

## Resources

- **Person** → `references/resources/Person.md` (132 ops) - A person record represents a single member/user of
- **List** → `references/resources/List.md` (48 ops) - A list is a powerful tool for finding and grouping
- **Workflow** → `references/resources/Workflow.md` (38 ops) - A Workflow
- **Form** → `references/resources/Form.md` (26 ops) - A custom form for people to fill out.
- **Household** → `references/resources/Household.md` (22 ops) - A household links people together and can have a p
- **FieldDatum** → `references/resources/FieldDatum.md` (20 ops) - A field datum is an individual piece of data for a
- **NoteCategory** → `references/resources/NoteCategory.md` (20 ops) - A Note Category
- **Note** → `references/resources/Note.md` (16 ops) - A note is text with a category connected to a pers
- **PeopleImport** → `references/resources/PeopleImport.md` (14 ops) - A PeopleImport is a record of an ongoing or previo
- **Tab** → `references/resources/Tab.md` (14 ops) - A tab is a custom tab and groups like field defini
- **Campus** → `references/resources/Campus.md` (13 ops) - A Campus is a location belonging to an Organizatio
- **FieldDefinition** → `references/resources/FieldDefinition.md` (13 ops) - A field definition represents a custom field -- it
- **Report** → `references/resources/Report.md` (13 ops) - A report is editable liquid syntax that provides a
- **MessageGroup** → `references/resources/MessageGroup.md` (10 ops) - A message group represents one or more emails or t
- **SchoolOption** → `references/resources/SchoolOption.md` (9 ops) - A school option represents a school name, school t
- **BackgroundCheck** → `references/resources/BackgroundCheck.md` (8 ops) - Background Checks for a Person
- **Email** → `references/resources/Email.md` (8 ops) - An email represents an email address and location.
- **ListCategory** → `references/resources/ListCategory.md` (8 ops) - A List Category
- **Message** → `references/resources/Message.md` (8 ops) - A message is an individual email or sms text sent 
- **SocialProfile** → `references/resources/SocialProfile.md` (8 ops) - A social profile represents a members's Twitter, F
- **NoteCategorySubscription** → `references/resources/NoteCategorySubscription.md` (6 ops) - A subscription for note categories
- **FormCategory** → `references/resources/FormCategory.md` (5 ops) - A Form Category
- **InactiveReason** → `references/resources/InactiveReason.md` (5 ops) - An inactive reason is a small bit of text indicati
- **MaritalStatus** → `references/resources/MaritalStatus.md` (5 ops) - A martial status represents a member's current sta
- **MembershipType** → `references/resources/MembershipType.md` (5 ops) - A profile's membership type, e.g. Visitor, Regular
- **NamePrefix** → `references/resources/NamePrefix.md` (5 ops) - A name prefix is one of Mr., Mrs., etc.
- **NameSuffix** → `references/resources/NameSuffix.md` (5 ops) - A name suffix is one of Sr., Jr., etc.
- **Address** → `references/resources/Address.md` (4 ops) - An address represents a physical and/or mailing ad
- **PhoneNumber** → `references/resources/PhoneNumber.md` (4 ops) - A phone number represents a single telephone numbe
- **App** → `references/resources/App.md` (2 ops) - An app is one of the handful of apps that Planning
- **person_mergers** → `references/resources/person-mergers.md` (2 ops)
- **SpamEmailAddress** → `references/resources/SpamEmailAddress.md` (2 ops) - An email address that is marked as spam
- **default** → `references/resources/default.md` (1 ops)
- **BirthdayPeople** → `references/resources/BirthdayPeople.md` (1 ops) - Returns upcoming birthdays for the organization.


- **Carrier** → `references/resources/Carrier.md` (1 ops)
- **OrganizationStatistics** → `references/resources/OrganizationStatistics.md` (1 ops) - Returns statistics for the organization.
