# 1. Introduction

## 1.1 Purpose
The purpose of this document is to get a detailed overview of which functionality is needed for "Confluence alternativ" application. The intended audience for this document are the developers to give a guidance of which functionality should or shall exist and the importance of the required functionality.
## 1.2 Scope
I have not found any good enough replacement for Confluence, that's open-source and free to use. Therefore this 
## 1.3 Definitions, acronyms, and abbreviations
| Term | Definition |
| ---- | ---------- |
| HTTP | **H**yper**T**ext **T**ransport **P**rotocol |
| WCAG | **W**eb **C**ontent **A**ccessibility **G**uidelines |
# 2. Overall description

## 2.1 Product perspective

## 2.2 Product functions

## 2.3 Intended users

## 2.4 Constratints

## 2.5 References

# 3. Requirements

## 3.1 Requirements layout

Requirements need to have the following layout:
- Requirment ID: ####
- Requirement type: SR, FR, EIR, NFR
    - SR - System requirement
    - FR - Functional requirement
    - EIR - External Interface Requirement
    - NFR - Non-Functional Requriement
- Priority: 1-5 (where 1 is urgent and 5 least urgent)
- Title: Short description of the requirement
- Content: Detailed information of the requiremnt
- Date of creation: YYYY-MM-DD

Example:
<table>
    <tbody>
        <tr>
            <td>
                Type: SR
            </td>
            <td>
                ID: 123
            </td>
            <td>
                DATE: 2021-02-14
            </td>
            <td>
                Priority: 1
            </td>
        </tr>
        <tr>
            <td colspan=4>
                This is the title of the requirement!
            </td>
        </tr>
        <tr>
            <td colspan=4>
                This is the description of the requirement
            </td>
        </tr>
    </tbody>
</table>

---

## 3.2 System reqruirments
Which OS shall the application requrie to run on.

Ram, CPU, disk space requirements.

## 3.3 Functional requirements
All functional requirements goes here

## 3.4 External interface requirements
Programming language, frameworks, way of communication between applications.

Client side support, for example: screen sizes.

## 3.5 Non-functional requirements
For example, system performance, code of conduct, kind of everything that can't be a function (but can still be part of a function, for example, rules for userfeedback in the UI), and graphic profile.
Practical example:
<table>
    <tbody>
        <tr>
            <td>
                Type: NFR
            </td>
            <td>
                ID: ###
            </td>
            <td>
                DATE: 2021-02-14
            </td>
            <td>
                Priority: 1
            </td>
        </tr>
        <tr>
            <td colspan=4>
                Response times
            </td>
        </tr>
        <tr>
            <td colspan=4>
                Tasks that take more than 1 second, shall display a loading feedback, for example a loading icon.
                </br>
                Tasks that take less than 1 second, is an instantaneous operation and does not need any feedback
                </br>
                Tasks that take more than 10 second, shall display a loading feedback, for example a loading icon and show an estimated time until completion if possible.
            </td>
        </tr>
    </tbody>
</table>

---

<table>
    <tbody>
        <tr>
            <td>
                Type: NFR
            </td>
            <td>
                ID: ###
            </td>
            <td>
                DATE: 2021-02-14
            </td>
            <td>
                Priority: 1
            </td>
        </tr>
        <tr>
            <td colspan=4>
                White labelling
            </td>
        </tr>
        <tr>
            <td colspan=4>
                Shall be easy to change colour scheme, logotype, organization name.
            </td>
        </tr>
    </tbody>
</table>