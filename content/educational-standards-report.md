---
title: "Educational Standards Report"
date: 2021-07-15T18:31:54-04:00
draft: true
tags: ["educational standard"]
author: Ming Wu

---
___

### **1. Lincoln Learning's example spreadsheets of standards data**

**Take Mathematics as an example**

**[Mathematics](https://docs.google.com/spreadsheets/d/14JYVMWmKHYgUC13mFV1LIf6GuX6qv8UC8Tw-ZriTpCU/edit#gid=0)**

![mathcourse-csv](/schoolsplp/mathcourse-csv.png)

### **2. Part of response result by making "cmd=getmanifest&entityid=161418259" API call**

**Folder_1 is all the data for Lesson 1, it consists of 6 items, each item is a task within this lesson**

```json
{
    "id": "Folder_1",
    "actualentityid": "131935737",
    "creationdate": "2020-06-16T17:29:22.4972384Z",
    "creationby": "70313930",
    "modifieddate": "2020-06-16T17:29:22.4972384Z",
    "modifiedby": "70313930",
    "data": {
        "parent": {
            "$value": "Module_2"
        },
        "sequence": {
            "$value": "a"
        },
        "title": {
            "$value": "Lesson 1"
        },
        "timetocomplete": {
            "$value": "PT1M"
        },
        "category": {
            "$value": 1
        },
        "categorysequence": {
            "$value": "b.a"
        },
        "period": {
            "inherit": true,
            "$value": 0
        },
        "groupsetid": {
            "$value": "-1"
        },
        "projectgroupsetid": {
            "$value": "-1"
        },
        "weight": {
            "$value": 100
        },
        "gradeentry": {
            "$value": 1
        },
        "inputtable": {
            "inherit": true,
            "$value": 0
        },
        "attemptlimit": {
            "$value": -1
        }
    },
    "item": [
        {
            "id": "95aadf83-7cb9-49a5-85bd-ee30184b4fb4",
            "actualentityid": "160528689",
            "creationdate": "2021-05-03T14:45:09.2543681Z",
            "creationby": "114151265",
            "modifieddate": "2021-05-03T14:45:09.2543681Z",
            "modifiedby": "114151265",
            "derivativedepth": 2,
            "data": {
                "link": {
                    "courseid": "27236148",
                    "itemid": "lls_gate_vIyRgUYFsai6dD",
                    "version": "3"
                },
                "type": {
                    "$value": "AssetLink"
                },
                "parent": {
                    "$value": "Folder_1"
                },
                "sequence": {
                    "$value": "a"
                },
                "title": {
                    "$value": "Construct Expressions - Read It"
                },
                "folder": {
                    "$value": "95aadf83-7cb9-49a5-85bd-ee30184b4fb4"
                },
                "href": {
                    "$value": "bltis://gate.lincolnlearningsolutions.org/provider/tool/vIyRgUYFsai6dD"
                },
                "timetocomplete": {
                    "$value": "PT1M"
                },
                "learningobjectives": {
                    "objective": [
                        {
                            "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                        }
                    ]
                },
                "category": {
                    "$value": 1
                },
                "categorysequence": {
                    "$value": "a."
                },
                "period": {
                    "$value": 0
                },
                "groupsetid": {
                    "$value": "-1"
                },
                "projectgroupsetid": {
                    "$value": "-1"
                },
                "masterythreshold": {
                    "$value": 0
                },
                "weight": {
                    "$value": 100
                },
                "gradeentry": {
                    "$value": 1
                },
                "inputtable": {
                    "$value": 0
                },
                "completiontrigger": {
                    "$value": 1
                },
                "graderule": {
                    "$value": 2
                },
                "thumbnail": {
                    "entityid": "27236148",
                    "$value": "Assets/images_ITs/icon_read.png"
                },
                "attemptlimit": {
                    "$value": -1
                },
                "meta-ittype": {
                    "$value": "Read"
                },
                "meta-creationdate": {
                    "$value": "2020-01-28T16:17:56"
                },
                "meta-reviseddate": {
                    "$value": "2020-01-28T16:17:56"
                },
                "meta-keywords": {
                    "meta-keyword": [
                        {
                            "$value": "Algebra II"
                        },
                        {
                            "$value": "Secondary"
                        },
                        {
                            "$value": "Read It"
                        },
                        {
                            "$value": "coefficient"
                        },
                        {
                            "$value": "expression"
                        },
                        {
                            "$value": "variables"
                        },
                        {
                            "$value": "term"
                        },
                        {
                            "$value": "factor"
                        }
                    ]
                },
                "meta-contentstandards": {
                    "meta-contentstandard": {
                        "$value": "CCSS.Math.Content.HSA-SSE.A.1a"
                    }
                },
                "meta-contentgradelevels": {
                    "meta-contentgradelevel": [
                        {
                            "$value": "9"
                        },
                        {
                            "$value": "10"
                        },
                        {
                            "$value": "11"
                        },
                        {
                            "$value": "12"
                        }
                    ]
                },
                "meta-contentsubjects": {
                    "$value": "Mathematics 9-12"
                }
            }
        },
        {
            "id": "3ddd134c-cebe-4baa-be7a-f50f22893d19",
            "actualentityid": "160528689",
            "creationdate": "2021-05-03T14:45:09.0980976Z",
            "creationby": "114151265",
            "modifieddate": "2021-05-03T14:45:09.0980976Z",
            "modifiedby": "114151265",
            "derivativedepth": 2,
            "data": {
                "link": {
                    "courseid": "27236148",
                    "itemid": "lls_gate_7P2WzAODo5eZLV",
                    "version": "3"
                },
                "type": {
                    "$value": "AssetLink"
                },
                "parent": {
                    "$value": "Folder_1"
                },
                "sequence": {
                    "$value": "b"
                },
                "title": {
                    "$value": "Construct Expressions - Practice It"
                },
                "folder": {
                    "$value": "3ddd134c-cebe-4baa-be7a-f50f22893d19"
                },
                "href": {
                    "$value": "bltis://gate.lincolnlearningsolutions.org/provider/tool/7P2WzAODo5eZLV"
                },
                "timetocomplete": {
                    "$value": "PT1M"
                },
                "learningobjectives": {
                    "objective": [
                        {
                            "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                        }
                    ]
                },
                "category": {
                    "$value": 1
                },
                "categorysequence": {
                    "$value": "a."
                },
                "period": {
                    "$value": 0
                },
                "groupsetid": {
                    "$value": "-1"
                },
                "projectgroupsetid": {
                    "$value": "-1"
                },
                "masterythreshold": {
                    "$value": 0
                },
                "weight": {
                    "$value": 100
                },
                "gradeentry": {
                    "$value": 1
                },
                "inputtable": {
                    "$value": 0
                },
                "completiontrigger": {
                    "$value": 1
                },
                "graderule": {
                    "$value": 2
                },
                "thumbnail": {
                    "entityid": "27236148",
                    "$value": "Assets/images_ITs/icon_practice.png"
                },
                "attemptlimit": {
                    "$value": -1
                },
                "meta-ittype": {
                    "$value": "Practice"
                },
                "meta-creationdate": {
                    "$value": "2020-01-28T16:20:26"
                },
                "meta-reviseddate": {
                    "$value": "2020-01-28T16:20:26"
                },
                "meta-keywords": {
                    "meta-keyword": [
                        {
                            "$value": "Algebra II"
                        },
                        {
                            "$value": "Secondary"
                        },
                        {
                            "$value": "Practice It"
                        },
                        {
                            "$value": "coefficient"
                        },
                        {
                            "$value": "expression"
                        },
                        {
                            "$value": "variables"
                        },
                        {
                            "$value": "term"
                        },
                        {
                            "$value": "factor"
                        }
                    ]
                },
                "meta-contentstandards": {
                    "meta-contentstandard": {
                        "$value": "CCSS.Math.Content.HSA-SSE.A.1a"
                    }
                },
                "meta-contentgradelevels": {
                    "meta-contentgradelevel": [
                        {
                            "$value": "9"
                        },
                        {
                            "$value": "10"
                        },
                        {
                            "$value": "11"
                        },
                        {
                            "$value": "12"
                        }
                    ]
                },
                "meta-contentsubjects": {
                    "$value": "Mathematics 9-12"
                }
            }
        },
        {
            "id": "557a6c40-81c6-4116-b1d4-369e03a1dd95",
            "actualentityid": "160528689",
            "creationdate": "2021-05-03T14:45:09.5200717Z",
            "creationby": "114151265",
            "modifieddate": "2021-05-03T14:45:09.5200717Z",
            "modifiedby": "114151265",
            "derivativedepth": 2,
            "data": {
                "link": {
                    "courseid": "27236148",
                    "itemid": "lls_gate_tVZd4uc0MoSQzq",
                    "version": "3"
                },
                "type": {
                    "$value": "AssetLink"
                },
                "parent": {
                    "$value": "Folder_1"
                },
                "sequence": {
                    "$value": "c"
                },
                "title": {
                    "$value": "Construct Expressions - Show It"
                },
                "folder": {
                    "$value": "557a6c40-81c6-4116-b1d4-369e03a1dd95"
                },
                "href": {
                    "$value": "bltis://gate.lincolnlearningsolutions.org/provider/tool/tVZd4uc0MoSQzq"
                },
                "timetocomplete": {
                    "$value": "PT1M"
                },
                "learningobjectives": {
                    "objective": [
                        {
                            "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                        }
                    ]
                },
                "category": {
                    "$value": 1
                },
                "categorysequence": {
                    "$value": "a."
                },
                "period": {
                    "$value": 0
                },
                "groupsetid": {
                    "$value": "-1"
                },
                "projectgroupsetid": {
                    "$value": "-1"
                },
                "masterythreshold": {
                    "$value": 0
                },
                "weight": {
                    "$value": 100
                },
                "gradeentry": {
                    "$value": 1
                },
                "inputtable": {
                    "$value": 0
                },
                "completiontrigger": {
                    "$value": 1
                },
                "graderule": {
                    "$value": 2
                },
                "thumbnail": {
                    "entityid": "27236148",
                    "$value": "Assets/images_ITs/icon_show.png"
                },
                "attemptlimit": {
                    "$value": -1
                },
                "meta-ittype": {
                    "$value": "Show"
                },
                "meta-creationdate": {
                    "$value": "2020-01-30T19:48:44"
                },
                "meta-reviseddate": {
                    "$value": "2020-01-30T19:48:44"
                },
                "meta-keywords": {
                    "meta-keyword": [
                        {
                            "$value": "Algebra II"
                        },
                        {
                            "$value": "Secondary"
                        },
                        {
                            "$value": "Show It"
                        },
                        {
                            "$value": "terms"
                        },
                        {
                            "$value": "factors"
                        },
                        {
                            "$value": "coefficient"
                        },
                        {
                            "$value": "exponents"
                        },
                        {
                            "$value": "constants"
                        }
                    ]
                },
                "meta-contentstandards": {
                    "meta-contentstandard": {
                        "$value": "CCSS.Math.Content.HSA-SSE.A.1a"
                    }
                },
                "meta-contentgradelevels": {
                    "meta-contentgradelevel": [
                        {
                            "$value": "9"
                        },
                        {
                            "$value": "10"
                        },
                        {
                            "$value": "11"
                        },
                        {
                            "$value": "12"
                        }
                    ]
                },
                "meta-contentsubjects": {
                    "$value": "Mathematics 9-12"
                }
            }
        },
        {
            "id": "7109d44c-aa22-4d8c-8431-c2afbc56a9b6",
            "actualentityid": "160528689",
            "creationdate": "2021-05-03T14:45:09.6605821Z",
            "creationby": "114151265",
            "modifieddate": "2021-05-03T14:45:09.6605821Z",
            "modifiedby": "114151265",
            "derivativedepth": 2,
            "data": {
                "link": {
                    "courseid": "27236148",
                    "itemid": "lls_gate_9amvyECdZfQHRi",
                    "version": "3"
                },
                "type": {
                    "$value": "AssetLink"
                },
                "parent": {
                    "$value": "Folder_1"
                },
                "sequence": {
                    "$value": "d"
                },
                "title": {
                    "$value": "Construct Expressions - Show It AK"
                },
                "folder": {
                    "$value": "7109d44c-aa22-4d8c-8431-c2afbc56a9b6"
                },
                "href": {
                    "$value": "bltis://gate.lincolnlearningsolutions.org/provider/tool/9amvyECdZfQHRi"
                },
                "timetocomplete": {
                    "$value": "PT1M"
                },
                "learningobjectives": {
                    "objective": [
                        {
                            "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                        }
                    ]
                },
                "category": {
                    "$value": 1
                },
                "categorysequence": {
                    "$value": "a."
                },
                "period": {
                    "$value": 0
                },
                "groupsetid": {
                    "$value": "-1"
                },
                "projectgroupsetid": {
                    "$value": "-1"
                },
                "masterythreshold": {
                    "$value": 0
                },
                "weight": {
                    "$value": 100
                },
                "gradeentry": {
                    "$value": 1
                },
                "inputtable": {
                    "$value": 0
                },
                "completiontrigger": {
                    "$value": 1
                },
                "graderule": {
                    "$value": 2
                },
                "thumbnail": {
                    "entityid": "27236148",
                    "$value": "Assets/images_ITs/icon_answer.png"
                },
                "attemptlimit": {
                    "$value": -1
                },
                "meta-creationdate": {
                    "$value": "2020-01-30T19:49:57"
                },
                "meta-reviseddate": {
                    "$value": "2020-01-30T19:49:57"
                },
                "meta-keywords": {
                    "meta-keyword": [
                        {
                            "$value": "Algebra II"
                        },
                        {
                            "$value": "Secondary"
                        },
                        {
                            "$value": "Show It AK"
                        },
                        {
                            "$value": "factors"
                        },
                        {
                            "$value": "coefficient"
                        },
                        {
                            "$value": "exponents"
                        },
                        {
                            "$value": "constants"
                        }
                    ]
                },
                "meta-contentstandards": {
                    "meta-contentstandard": {
                        "$value": "CCSS.Math.Content.HSA-SSE.A.1a"
                    }
                },
                "meta-contentgradelevels": {
                    "meta-contentgradelevel": [
                        {
                            "$value": "9"
                        },
                        {
                            "$value": "10"
                        },
                        {
                            "$value": "11"
                        },
                        {
                            "$value": "12"
                        }
                    ]
                },
                "meta-contentsubjects": {
                    "$value": "Mathematics 9-12"
                }
            }
        },
        {
            "id": "267fa892-dee0-4be0-8ac8-d72cc129d642",
            "actualentityid": "160528689",
            "creationdate": "2021-04-29T22:49:36.0236762Z",
            "creationby": "114151265",
            "modifieddate": "2021-05-03T14:45:08.8354547Z",
            "modifiedby": "114151265",
            "derivativedepth": 2,
            "data": {
                "link": {
                    "courseid": "71945679",
                    "itemid": "71945679_Construct_Expressions_1920",
                    "version": "8"
                },
                "type": {
                    "$value": "Assessment"
                },
                "parent": {
                    "$value": "Folder_1"
                },
                "sequence": {
                    "$value": "e"
                },
                "title": {
                    "$value": "Construct Expressions - Assess It"
                },
                "folder": {
                    "$value": "267fa892-dee0-4be0-8ac8-d72cc129d642"
                },
                "href": {
                    "entityid": "71945679",
                    "$value": "Templates/Data/71945679_Construct_Expressions_1920/index.html"
                },
                "timetocomplete": {
                    "$value": "PT1M"
                },
                "learningobjectives": {
                    "objective": [
                        {
                            "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                        },
                        {
                            "guid": "231ab554-2292-0607-fb61-f21adcebc944"
                        }
                    ]
                },
                "category": {
                    "$value": 2
                },
                "categorysequence": {
                    "$value": "b.a.e"
                },
                "period": {
                    "inherit": true,
                    "$value": 0
                },
                "groupsetid": {
                    "$value": "-1"
                },
                "projectgroupsetid": {
                    "$value": "-1"
                },
                "hiddenfromstudent": {
                    "$value": true
                },
                "visibility": {
                    "$value": 8
                },
                "gradable": {
                    "$value": true
                },
                "masterythreshold": {
                    "$value": 0
                },
                "weight": {
                    "$value": 100
                },
                "gradeentry": {
                    "$value": 1
                },
                "inputtable": {
                    "inherit": true,
                    "$value": 0
                },
                "completiontrigger": {
                    "$value": 1
                },
                "graderule": {
                    "$value": 2
                },
                "flags": {
                    "$value": 1
                },
                "thumbnail": {
                    "entityid": "71945679",
                    "$value": "Assets/images_ITs/icon_assess.png"
                },
                "questions": {
                    "question": [
                        {
                            "entityid": "71945679",
                            "id": "9fb796c98e8844dfbc915509f3dfaf16",
                            "type": 1,
                            "referrer": "161418259:267fa892-dee0-4be0-8ac8-d72cc129d642"
                        },
                        {
                            "entityid": "71945679",
                            "id": "c27c9de58f194e73936f71af8bbc0295",
                            "type": 1,
                            "referrer": "161418259:267fa892-dee0-4be0-8ac8-d72cc129d642"
                        },
                        {
                            "entityid": "71945679",
                            "id": "adb3394bc95e4083864fa2b02b456cf1",
                            "type": 1,
                            "referrer": "161418259:267fa892-dee0-4be0-8ac8-d72cc129d642"
                        },
                        {
                            "entityid": "71945679",
                            "id": "6adc0bd24af544a382ebca9ad797bbdb",
                            "type": 1,
                            "referrer": "161418259:267fa892-dee0-4be0-8ac8-d72cc129d642"
                        },
                        {
                            "entityid": "71945679",
                            "id": "da12c11aefac46a096493cfa054a18d9",
                            "type": 1,
                            "referrer": "161418259:267fa892-dee0-4be0-8ac8-d72cc129d642"
                        }
                    ]
                },
                "examflags": {
                    "$value": "1999110"
                },
                "attemptlimit": {
                    "$value": 1
                },
                "questionsperpage": {
                    "$value": 1
                },
                "securitylevel": {
                    "$value": "Low"
                },
                "examreviewrules": {
                    "rule": [
                        {
                            "setting": "Answer",
                            "condition": "true"
                        },
                        {
                            "setting": "Achieved",
                            "condition": "true"
                        },
                        {
                            "setting": "Possible",
                            "condition": "true"
                        },
                        {
                            "setting": "CorrectQuestion",
                            "condition": "true"
                        },
                        {
                            "setting": "Feedback",
                            "condition": "false"
                        },
                        {
                            "setting": "CorrectChoice",
                            "condition": "false"
                        }
                    ]
                }
            }
        },
        {
            "id": "397275be-54d6-435e-9664-f70b16b49795",
            "actualentityid": "160528689",
            "creationdate": "2021-05-03T14:45:09.3948458Z",
            "creationby": "114151265",
            "modifieddate": "2021-05-03T14:45:09.3948458Z",
            "modifiedby": "114151265",
            "derivativedepth": 2,
            "data": {
                "link": {
                    "courseid": "27236148",
                    "itemid": "lls_gate_be6n3sJUkyXFNt",
                    "version": "3"
                },
                "type": {
                    "$value": "AssetLink"
                },
                "parent": {
                    "$value": "Folder_1"
                },
                "sequence": {
                    "$value": "f"
                },
                "title": {
                    "$value": "Construct Expressions - Reinforce It"
                },
                "folder": {
                    "$value": "397275be-54d6-435e-9664-f70b16b49795"
                },
                "href": {
                    "$value": "bltis://gate.lincolnlearningsolutions.org/provider/tool/be6n3sJUkyXFNt"
                },
                "timetocomplete": {
                    "$value": "PT1M"
                },
                "learningobjectives": {
                    "objective": [
                        {
                            "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                        }
                    ]
                },
                "category": {
                    "$value": 1
                },
                "categorysequence": {
                    "$value": "a."
                },
                "period": {
                    "$value": 0
                },
                "groupsetid": {
                    "$value": "-1"
                },
                "projectgroupsetid": {
                    "$value": "-1"
                },
                "masterythreshold": {
                    "$value": 0
                },
                "weight": {
                    "$value": 100
                },
                "gradeentry": {
                    "$value": 1
                },
                "inputtable": {
                    "$value": 0
                },
                "completiontrigger": {
                    "$value": 1
                },
                "graderule": {
                    "$value": 2
                },
                "thumbnail": {
                    "entityid": "27236148",
                    "$value": "Assets/images_ITs/icon_reinforce.png"
                },
                "attemptlimit": {
                    "$value": -1
                },
                "meta-ittype": {
                    "$value": "Reinforce"
                },
                "meta-creationdate": {
                    "$value": "2020-02-24T14:40:22"
                },
                "meta-reviseddate": {
                    "$value": "2020-02-24T14:40:22"
                },
                "meta-keywords": {
                    "meta-keyword": [
                        {
                            "$value": "Algebra II"
                        },
                        {
                            "$value": "secondary"
                        },
                        {
                            "$value": "Reinforce It"
                        },
                        {
                            "$value": "coefficient"
                        },
                        {
                            "$value": "terms"
                        }
                    ]
                },
                "meta-contentstandards": {
                    "meta-contentstandard": {
                        "$value": "CCSS.Math.Content.HSA-SSE.A.1a"
                    }
                },
                "meta-contentgradelevels": {
                    "meta-contentgradelevel": [
                        {
                            "$value": "9"
                        },
                        {
                            "$value": "10"
                        },
                        {
                            "$value": "11"
                        },
                        {
                            "$value": "12"
                        }
                    ]
                },
                "meta-contentsubjects": {
                    "$value": "Mathematics 9-12"
                }
            }
        }
    ]
}
```

### **3. Take one item to analyze**

**Item 1 in Lesson 1 with ID=lls_gate_vIyRgUYFsai6dD which is also the ID in Spreadsheet**

[Item Data](https://api.agilixbuzz.com/docs/#!/Schema/ItemData)

|LO Name|	Type (It)|	Primary Standard|	Standard Description|	ID|
|--------|-------|---------------------|------------------------|------|		
|Lesson 1|	Lesson|	Lesson|		
|Construct Expressions|	Read It|	CCSS.Math.Content.HSA-SSE.A.1a	|Interpret parts of an expression, such as terms, factors, and coefficients.	|lls_gate_vIyRgUYFsai6dD|
|Construct Expressions|	Practice It|	CCSS.Math.Content.HSA-SSE.A.1a	|Interpret parts of an expression, such as terms, factors, and coefficients.	|lls_gate_7P2WzAODo5eZLV|
|Construct Expressions|	Show It|	CCSS.Math.Content.HSA-SSE.A.1a	|Interpret parts of an expression, such as terms, factors, and coefficients.	|lls_gate_tVZd4uc0MoSQzq|
|Construct Expressions|	Show It| AK	CCSS.Math.Content.HSA-SSE.A.1a	|Interpret parts of an expression, such as terms, factors, and coefficients.	|lls_gate_9amvyECdZfQHRi|
|Construct Expressions|	Assess It|	CCSS.Math.Content.HSA-SSE.A.1a	|Interpret parts of an expression, such as terms, factors, and coefficients.|	|
|Construct Expressions|	Reinforce It|	CCSS.Math.Content.HSA-SSE.A.1a	|Interpret parts of an expression, such as terms, factors, and coefficients.	|lls_gate_be6n3sJUkyXFNt|

```json
{
    "id": "95aadf83-7cb9-49a5-85bd-ee30184b4fb4",
    "actualentityid": "160528689",
    "creationdate": "2021-05-03T14:45:09.2543681Z",
    "creationby": "114151265",
    "modifieddate": "2021-05-03T14:45:09.2543681Z",
    "modifiedby": "114151265",
    "derivativedepth": 2,
    "data": {
        "link": {
            "courseid": "27236148",
            "itemid": "lls_gate_vIyRgUYFsai6dD",
            "version": "3"
        },
        "type": {
            "$value": "AssetLink"
        },
        "parent": {
            "$value": "Folder_1"
        },
        "sequence": {
            "$value": "a"
        },
        "title": {
            "$value": "Construct Expressions - Read It"
        },
        "folder": {
            "$value": "95aadf83-7cb9-49a5-85bd-ee30184b4fb4"
        },
        "href": {
            "$value": "bltis://gate.lincolnlearningsolutions.org/provider/tool/vIyRgUYFsai6dD"
        },
        "timetocomplete": {
            "$value": "PT1M"
        },
        "learningobjectives": {
            "objective": [
                {
                    "guid": "52bd5519-acd2-415e-bab6-a0b342bc8ab2"
                }
            ]
        },
        "category": {
            "$value": 1
        },
        "categorysequence": {
            "$value": "a."
        },
        "period": {
            "$value": 0
        },
        "groupsetid": {
            "$value": "-1"
        },
        "projectgroupsetid": {
            "$value": "-1"
        },
        "masterythreshold": {
            "$value": 0
        },
        "weight": {
            "$value": 100
        },
        "gradeentry": {
            "$value": 1
        },
        "inputtable": {
            "$value": 0
        },
        "completiontrigger": {
            "$value": 1
        },
        "graderule": {
            "$value": 2
        },
        "thumbnail": {
            "entityid": "27236148",
            "$value": "Assets/images_ITs/icon_read.png"
        },
        "attemptlimit": {
            "$value": -1
        },
        "meta-ittype": {
            "$value": "Read"
        },
        "meta-creationdate": {
            "$value": "2020-01-28T16:17:56"
        },
        "meta-reviseddate": {
            "$value": "2020-01-28T16:17:56"
        },
        "meta-keywords": {
            "meta-keyword": [
                {
                    "$value": "Algebra II"
                },
                {
                    "$value": "Secondary"
                },
                {
                    "$value": "Read It"
                },
                {
                    "$value": "coefficient"
                },
                {
                    "$value": "expression"
                },
                {
                    "$value": "variables"
                },
                {
                    "$value": "term"
                },
                {
                    "$value": "factor"
                }
            ]
        },
        "meta-contentstandards": {
            "meta-contentstandard": {
                "$value": "CCSS.Math.Content.HSA-SSE.A.1a"
            }
        },
        "meta-contentgradelevels": {
            "meta-contentgradelevel": [
                {
                    "$value": "9"
                },
                {
                    "$value": "10"
                },
                {
                    "$value": "11"
                },
                {
                    "$value": "12"
                }
            ]
        },
        "meta-contentsubjects": {
            "$value": "Mathematics 9-12"
        }
    }
}
```

![Algebra](/schoolsplp/Algebra-2A.png)

![Courses-Relationship](/schoolsplp/courses-relationship.png)

**Note :**

1. The **actualentityid** within each item is actually the basecourse id 

2. We can easily call getitem to get the item infomation and setup the correspondence between **items** and **DLAP (Course ID, Item ID) pair**

**Why I can't find the item by the following call ? Like I don't have the right to make this api call**

>Call by base course id

**cmd=getitem&entityid=160528689&itemid=lls_gate_vIyRgUYFsai6dD**

**Response:**
```json
{
  "response":{
    "code":"ResourceNotFound",
    "message":"Resource not found: EntityId='160528689', Path='lls_gate_vIyRgUYFsai6dD'.",
    "errorId":"34954040acb247d0bc647f50bf57c043"
  }
}
```

>Call by course id

**cmd=getitem&entityid=161418259&itemid=lls_gate_vIyRgUYFsai6dD**

**Response:**
```json
{
  "response":{
    "code":"ResourceNotFound",
    "message":"Resource not found: EntityId='161418259', Path='lls_gate_vIyRgUYFsai6dD'.",
    "errorId":"8c55c79b2ed148748de4f732dadaf5d9"
  }
}
```

>Call by courseid in link data

**cmd=getitem&entityid=27236148&itemid=lls_gate_vIyRgUYFsai6dD**

```json
"link": {
    "courseid": "27236148",
    "itemid": "lls_gate_vIyRgUYFsai6dD",
    "version": "3"
}
```

**Response:**
```json
{
  "response":{
    "code":"AccessDenied",
    "message":"Access Denied: userId='160282061'",
    "errorId":"db1ea8a51e95482c955eb121213e2dc4"
  }
}
```