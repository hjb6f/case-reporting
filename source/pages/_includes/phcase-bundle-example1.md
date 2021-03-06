<p>
<a href="../assets/json/phcase-bundle-example1.json" download>download json file</a>
</p>

~~~json

{
   "resourceType":"Bundle",
   "id":"phcase-bundle",
   "meta":{
      "lastUpdated":"2014-08-18T01:43:30Z"
   },
   "type":"searchset",
   "total":11,
   "entry":[
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Immunization/phcase-pneumo",
         "resource":{
            "date":"1998-12-15",
            "id":"phcase-pneumo",
            "notGiven":false,
            "patient":{
               "display":"Eve Everywoman",
               "reference":"Patient/phcase-js"
            },
            "primarySource":false,
            "resourceType":"Immunization",
            "status":"completed",
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-pneumo</p><p><b>status</b>: completed</p><p><b>notGiven</b>: false</p><p><b>vaccineCode</b>: Pneumococcal polysaccharide vaccine <span style=\"background: LightGoldenRodYellow\">(Details : {http://hl7.org/fhir/sid/cvx code '33' = 'pneumococcal polysaccharide PPV23', given as 'Pneumococcal polysaccharide vaccine'})</span></p><p><b>patient</b>: <a href=\"Patient-phcase-js.html\">Eve Everywoman. Generated Summary: id: phcase-js; Medical Record Number = 1032702 (USUAL), SSN = 11-00-1234 (USUAL); active; Eve L Everywoman ; ph: 1-(404)555-1212(HOME), eve.everywoman@example.com; gender: female; birthDate: Nov 24, 1974</a></p><p><b>date</b>: Dec 15, 1998</p><p><b>primarySource</b>: false</p></div>",
               "status":"generated"
            },
            "vaccineCode":{
               "coding":[
                  {
                     "code":"33",
                     "display":"Pneumococcal polysaccharide vaccine",
                     "system":"http://hl7.org/fhir/sid/cvx"
                  }
               ]
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Location/phcase-fj",
         "resource":{
            "address":{
               "city":"Nadi",
               "country":"Fiji"
            },
            "id":"phcase-fj",
            "name":"Fiji",
            "physicalType":{
               "coding":[
                  {
                     "code":"jdn",
                     "display":"Jurisdiction",
                     "system":"http://hl7.org/fhir/location-physical-type"
                  }
               ]
            },
            "resourceType":"Location",
            "status":"active",
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-fj</p><p><b>status</b>: active</p><p><b>name</b>: Fiji</p><p><b>address</b>: Nadi Fiji </p><p><b>physicalType</b>: Jurisdiction <span style=\"background: LightGoldenRodYellow\">(Details : {http://hl7.org/fhir/location-physical-type code 'jdn' = 'Jurisdiction', given as 'Jurisdiction'})</span></p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Location/phcase-smc",
         "resource":{
            "address":{
               "city":"Ann Arbor",
               "line":[
                  "Clinic Bldg A",
                  "4444 Healthcare Drive"
               ],
               "postalCode":"99999",
               "state":"MI",
               "text":"Clinic Bldg A, 4444 Healthcare Drive, Ann Arbor, MI 99999"
            },
            "id":"phcase-smc",
            "managingOrganization":{
               "reference":"Organization/smc"
            },
            "meta":{
               "profile":[
                  "http://fhir.org/guides/argonaut-pd/StructureDefinition/argo-location"
               ]
            },
            "name":"Clinic Bldg A, Salem Medical Center",
            "resourceType":"Location",
            "status":"active",
            "telecom":[
               {
                  "system":"phone",
                  "value":"(+1) (555)555-3001"
               },
               {
                  "system":"fax",
                  "value":"(+1) (555)555-3002"
               },
               {
                  "system":"email",
                  "value":"mail@smc.org"
               }
            ],
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-smc</p><p><b>meta</b>: </p><p><b>status</b>: active</p><p><b>name</b>: Clinic Bldg A, Salem Medical Center</p><p><b>telecom</b>: ph: (+1) (555)555-3001, fax: (+1) (555)555-3002, mail@smc.org</p><p><b>address</b>: Clinic Bldg A, 4444 Healthcare Drive, Ann Arbor, MI 99999</p><p><b>managingOrganization</b>: <a href=\"Organization/smc\">Organization/smc</a></p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/MedicationStatement/phcase-azithro",
         "resource":{
            "dateAsserted":"2016-11-07T16:13:03Z",
            "dosage":[
               {
                  "doseQuantity":{
                     "code":"TAB",
                     "system":"http://hl7.org/fhir/v3/orderableDrugForm",
                     "unit":"TAB",
                     "value":1
                  },
                  "route":{
                     "coding":[
                        {
                           "code":"C38288",
                           "display":"ORALLY",
                           "system":"http://ncimeta.nci.nih.gov",
                           "userSelected":false
                        }
                     ]
                  },
                  "timing":{
                     "repeat":{
                        "count":1
                     }
                  }
               }
            ],
            "effectivePeriod":{
               "end":"2016-11-07",
               "start":"2016-11-07"
            },
            "id":"phcase-azithro",
            "medicationCodeableConcept":{
               "coding":[
                  {
                     "code":"248656",
                     "display":"Azithromycin 500 MG Oral Tablet",
                     "system":"http://www.nlm.nih.gov/research/umls/rxnorm"
                  }
               ],
               "text":"Azithromycin 500 MG Oral Tablet"
            },
            "meta":{
               "profile":[
                  "http://hl7.org/fhir/us/core/StructureDefinition/us-core-medicationstatement"
               ]
            },
            "resourceType":"MedicationStatement",
            "status":"active",
            "subject":{
               "display":"Eve Everywoman",
               "reference":"Patient/phcase-js"
            },
            "taken":"y",
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-azithro</p><p><b>meta</b>: </p><p><b>status</b>: active</p><p><b>medication</b>: Azithromycin 500 MG Oral Tablet <span style=\"background: LightGoldenRodYellow\">(Details : {RxNorm code '248656' = 'azithromycin 500 MG Oral Tablet', given as 'Azithromycin 500 MG Oral Tablet'})</span></p><p><b>effective</b>: Nov 7, 2016 --&gt; Nov 7, 2016</p><p><b>dateAsserted</b>: Nov 7, 2016 4:13:03 PM</p><p><b>subject</b>: <a href=\"Patient-phcase-js.html\">Eve Everywoman. Generated Summary: id: phcase-js; Medical Record Number = 1032702 (USUAL), SSN = 11-00-1234 (USUAL); active; Eve L Everywoman ; ph: 1-(404)555-1212(HOME), eve.everywoman@example.com; gender: female; birthDate: Nov 24, 1974</a></p><p><b>taken</b>: y</p><p><b>dosage</b>: </p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Observation/phcase-pert",
         "resource":{
            "code":{
               "coding":[
                  {
                     "code":"548-8",
                     "display":"Bordetella pertussis [Presence] in Throat by Organism specific culture",
                     "system":"http://loinc.org"
                  }
               ],
               "text":"Bordetella Throat culture"
            },
            "id":"phcase-pert",
            "identifier":[
               {
                  "system":"https://acme.labs/identifiers",
                  "type":{
                     "coding":[
                        {
                           "code":"FILL",
                           "display":"Filler Identifier",
                           "system":"http://hl7.org/fhir/identifier-type"
                        }
                     ],
                     "text":"Filler Identifier"
                  },
                  "value":"7d5a02b0-67a4-11db-bd13-0800200c9a66"
               }
            ],
            "issued":"2016-11-07T10:28:00+01:00",
            "meta":{
               "profile":[
                  "http://hl7.org/fhir/us/core/StructureDefinition/us-core-observationresults"
               ]
            },
            "performer":[
               {
                  "display":"Henry Seven, M.D.",
                  "reference":"Practitioner/phcase-mc"
               }
            ],
            "resourceType":"Observation",
            "status":"final",
            "subject":{
               "display":"Everywoman",
               "reference":"Patient/phcase-js"
            },
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-pert</p><p><b>meta</b>: </p><p><b>identifier</b>: Filler Identifier = 7d5a02b0-67a4-11db-bd13-0800200c9a66</p><p><b>status</b>: final</p><p><b>code</b>: Bordetella Throat culture <span style=\"background: LightGoldenRodYellow\">(Details : {LOINC code '548-8' = 'Bordetella pertussis [Presence] in Throat by Organism specific culture', given as 'Bordetella pertussis [Presence] in Throat by Organism specific culture'})</span></p><p><b>subject</b>: <a href=\"Patient-phcase-js.html\">Everywoman. Generated Summary: id: phcase-js; Medical Record Number = 1032702 (USUAL), SSN = 11-00-1234 (USUAL); active; Eve L Everywoman ; ph: 1-(404)555-1212(HOME), eve.everywoman@example.com; gender: female; birthDate: Nov 24, 1974</a></p><p><b>issued</b>: Nov 7, 2016 10:28:00 AM</p><p><b>performer</b>: <a href=\"Practitioner-phcase-mc.html\">Henry Seven, M.D.. Generated Summary: id: phcase-mc; 1521001101; Seven Henry </a></p><p><b>value</b>: Bordetella pertussis <span style=\"background: LightGoldenRodYellow\">(Details : {SNOMED CT code '5247005' = 'Hemophilus pertussis', given as 'Bordetella pertussis (organism)'})</span></p></div>",
               "status":"generated"
            },
            "valueCodeableConcept":{
               "coding":[
                  {
                     "code":"5247005",
                     "display":"Bordetella pertussis (organism)",
                     "system":"http://snomed.info/sct"
                  }
               ],
               "text":"Bordetella pertussis"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Organization/phcase-healthwest",
         "resource":{
            "active":true,
            "address":[
               {
                  "city":"Ann Arbor",
                  "line":[
                     "7777 Health Authority Drive"
                  ],
                  "postalCode":"99999",
                  "state":"MI",
                  "text":"7777 Health Authority Drive, Ann Arbor MI, 99999"
               }
            ],
            "id":"phcase-healthwest",
            "identifier":[
               {
                  "system":"http://hl7.org.fhir/sid/us-npi",
                  "value":"1144221847"
               }
            ],
            "meta":{
               "profile":[
                  "http://fhir.org/guides/argonaut-pd/StructureDefinition/argo-organization"
               ]
            },
            "name":"Health Authority West",
            "resourceType":"Organization",
            "telecom":[
               {
                  "system":"phone",
                  "value":"+1-555-555-3555"
               },
               {
                  "system":"email",
                  "value":"mail@healthauthoritywest.gov"
               }
            ],
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-healthwest</p><p><b>meta</b>: </p><p><b>identifier</b>: 1144221847</p><p><b>active</b>: true</p><p><b>type</b>: Public Health Agency <span style=\"background: LightGoldenRodYellow\">(Details : {http://hl7.org/fhir/us/ecr/CodeSystem/organization-type code 'pha' = 'pha', given as 'Public Health Agency'})</span></p><p><b>name</b>: Health Authority West</p><p><b>telecom</b>: ph: +1-555-555-3555, mail@healthauthoritywest.gov</p><p><b>address</b>: 7777 Health Authority Drive, Ann Arbor MI, 99999</p></div>",
               "status":"generated"
            },
            "type":[
               {
                  "coding":[
                     {
                        "code":"pha",
                        "display":"Public Health Agency",
                        "system":"http://hl7.org/fhir/us/ecr/CodeSystem/organization-type"
                     }
                  ]
               }
            ]
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Patient/phcase-js",
         "resource":{
            "active":true,
            "address":[
               {
                  "city":"Atlanta",
                  "country":"US",
                  "line":[
                     "5101 Peachtree St NE"
                  ],
                  "postalCode":"30302",
                  "state":"GA"
               }
            ],
            "birthDate":"1974-11-24",
            "extension":[
               {
                  "extension":[
                     {
                        "url":"ombCategory",
                        "valueCoding":{
                           "code":"2106-3",
                           "display":"White",
                           "system":"urn:oid:2.16.840.1.113883.6.238"
                        }
                     },
                     {
                        "url":"text",
                        "valueString":"White"
                     }
                  ],
                  "url":"http://hl7.org/fhir/us/core/StructureDefinition/us-core-race"
               },
               {
                  "extension":[
                     {
                        "url":"ombCategory",
                        "valueCoding":{
                           "code":"2186-5",
                           "display":"Not Hispanic or Latino",
                           "system":"urn:oid:2.16.840.1.113883.6.238"
                        }
                     },
                     {
                        "url":"text",
                        "valueString":"Not Hispanic or Latino"
                     }
                  ],
                  "url":"http://hl7.org/fhir/us/core/StructureDefinition/us-core-ethnicity"
               },
               {
                  "url":"http://hl7.org/fhir/us/core/StructureDefinition/us-core-birthsex",
                  "valueCode":"F"
               }
            ],
            "gender":"female",
            "id":"phcase-js",
            "identifier":[
               {
                  "system":"http://hospital.smarthealthit.org",
                  "type":{
                     "coding":[
                        {
                           "code":"MR",
                           "display":"Medical Record Number",
                           "system":"http://hl7.org/fhir/v2/0203"
                        }
                     ],
                     "text":"Medical Record Number"
                  },
                  "use":"usual",
                  "value":"1032702"
               },
               {
                  "system":"http://hl7.org/fhir/sid/us-ssn",
                  "type":{
                     "coding":[
                        {
                           "code":"SB",
                           "display":"Social Beneficiary Identifier",
                           "system":"http://hl7.org/fhir/identifier-type"
                        }
                     ],
                     "text":"SSN"
                  },
                  "use":"usual",
                  "value":"11-00-1234"
               }
            ],
            "meta":{
               "profile":[
                  "http://hl7.org/fhir/us/core/StructureDefinition/us-core-patient"
               ]
            },
            "name":[
               {
                  "family":"Everywoman",
                  "given":[
                     "Eve",
                     "L"
                  ]
               }
            ],
            "resourceType":"Patient",
            "telecom":[
               {
                  "system":"phone",
                  "use":"home",
                  "value":"1-(404)555-1212"
               },
               {
                  "system":"email",
                  "value":"eve.everywoman@example.com"
               }
            ],
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-js</p><p><b>meta</b>: </p><p><b>identifier</b>: Medical Record Number = 1032702 (USUAL), SSN = 11-00-1234 (USUAL)</p><p><b>active</b>: true</p><p><b>name</b>: Eve L Everywoman </p><p><b>telecom</b>: ph: 1-(404)555-1212(HOME), eve.everywoman@example.com</p><p><b>gender</b>: female</p><p><b>birthDate</b>: Nov 24, 1974</p><p><b>address</b>: 5101 Peachtree St NE Atlanta GA 30302 US </p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/PHCase/phcase-1",
         "resource":{
            "category":{
               "coding":[
                  {
                     "code":"40733004",
                     "display":"Infective disorder",
                     "system":"http://snomed.info/sct"
                  }
               ],
               "text":"Infectious Diseases"
            },
            "clinicalFindings":[
               {
                  "code":{
                     "text":"not pregnant"
                  }
               },
               {
                  "code":{
                     "coding":[
                        {
                           "code":"43025008",
                           "display":"Paroxysmal cough (finding)",
                           "system":"http://snomed.info/sct"
                        }
                     ]
                  }
               },
               {
                  "code":{
                     "text":"Persistent Cough REPORTED starting on 2016/10/05"
                  }
               },
               {
                  "code":{
                     "text":"Dark stools"
                  }
               },
               {
                  "code":{
                     "coding":[
                        {
                           "code":"27836007",
                           "display":"Pertussis",
                           "system":"http://snomed.info/sct"
                        }
                     ]
                  },
                  "isReasonExtension":"TRUE"
               },
               {
                  "isReasonExtension":"TRUE",
                  "reference":{
                     "display":"Bordetella pertussis [Presence] in Throat by Organism specific culture",
                     "reference":"Observation/phcase-pert"
                  }
               },
               {
                  "reference":{
                     "display":"Pneumococcal polysaccharide vaccine",
                     "reference":"Immunization/phcase-pneumo"
                  }
               }
            ],
            "code":{
               "coding":[
                  {
                     "code":"27836007",
                     "display":"Pertussis (disorder)",
                     "system":"http://snomed.info/sct"
                  }
               ],
               "text":"Pertussis"
            },
            "effectivePeriod":{
               "start":"2017-11-07"
            },
            "id":"phcase-1",
            "identifier":[
               {
                  "system":"https://healthauthoritywest.com/case-identifier",
                  "type":{
                     "coding":[
                        {
                           "code":"case-identifier",
                           "display":"Case Identifier",
                           "system":"http://hl7.org/fhir/us/ecr/CodeSystem/identifier-type"
                        }
                     ]
                  },
                  "value":"CS12346"
               }
            ],
            "jurisdiction":{
               "display":"Health Authority West",
               "reference":"Organization/phcase-healthwest"
            },
            "location":{
               "display":"Salem Medical Center,  4646 Brown Rd, Salem, MA  02368",
               "reference":"Location/phcase-smc"
            },
            "meta":{
               "lastUpdated":"2017-10-04T16:23:29.142584",
               "versionID":"ver2"
            },
            "note":[
               {
                  "text":"This is an example using the draft Case Resource",
                  "time":"2017-10-4"
               }
            ],
            "occupationCode":[
               {
                  "text":"Centers for Disease Control 1, Peachtree St South Atlanta, GA, 404-564-7865  Since JAN 1, 1993"
               }
            ],
            "orderedDiagnostics":[
               {
                  "isReasonExtension":"TRUE",
                  "reference":{
                     "display":"Zika virus envelope (E) gene [Presence] in Serum by Probe and target amplification method",
                     "reference":"ProcedureRequest/phcase-zika"
                  }
               }
            ],
            "reporter":{
               "display":"Henry Seven, M.D.",
               "reference":"PractitionerRole/phcase-mc"
            },
            "resourceType":"PHCase",
            "status":"in-progress",
            "subject":{
               "display":"Eve Everywoman",
               "reference":"Patient/phcase-js"
            },
            "travel-history":[
               {
                  "date":{
                     "end":"2007",
                     "start":"1999"
                  },
                  "locationCode":{
                     "text":"1999 to 2007 Spent 8 years in the UK during the BSE outbreak,  In the 3 weeks before NOV 9, 2016 "
                  }
               },
               {
                  "date":{
                     "end":"2016-10-30",
                     "start":"2106-04-29"
                  },
                  "locationCode":{
                     "coding":[
                        {
                           "code":"BRA",
                           "display":"Brazil",
                           "system":"urn:iso:std:iso:3166"
                        }
                     ],
                     "text":" Brazil"
                  }
               },
               {
                  "date":{
                     "end":"2016-06-13",
                     "start":"2016-7-05"
                  },
                  "locationReference":{
                     "display":"Nadi, FJ",
                     "reference":"Location/phcase-fj"
                  }
               }
            ],
            "treatments":[
               {
                  "display":"Azithromycin 500 MG Oral Tablet",
                  "reference":"MedicationStatement/phcase-azithro"
               }
            ]
         },
         "search":{
            "mode":"match",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/Practitioner/phcase-mc",
         "resource":{
            "address":[
               {
                  "city":"Burlington",
                  "country":"US",
                  "line":[
                     "BMass Doctors",
                     "2100 North Ave"
                  ],
                  "postalCode":"02368",
                  "state":"MA",
                  "text":"BMass Doctors"
               }
            ],
            "id":"phcase-mc",
            "identifier":[
               {
                  "system":"http://hl7.org.fhir/sid/us-npi",
                  "value":"1521001101"
               }
            ],
            "meta":{
               "profile":[
                  "http://hl7.org/fhir/us/core/StructureDefinition/us-core-practitioner"
               ]
            },
            "name":[
               {
                  "family":"Henry",
                  "given":[
                     "Seven"
                  ],
                  "suffix":[
                     "M,D,"
                  ]
               }
            ],
            "resourceType":"Practitioner",
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-mc</p><p><b>meta</b>: </p><p><b>identifier</b>: 1521001101</p><p><b>name</b>: Seven Henry </p><p><b>address</b>: BMass Doctors</p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/PractitionerRole/phcase-mc",
         "resource":{
            "code":[
               {
                  "coding":[
                     {
                        "code":"doctor",
                        "display":"Doctor",
                        "system":"http://hl7.org/fhir/practitioner-role"
                     }
                  ]
               }
            ],
            "endpoint":[
               {
                  "display":"henry.seven.MD@direct.smc.org",
                  "reference":"Endpoint/phcase-mcdirect"
               }
            ],
            "id":"phcase-mc",
            "location":[
               {
                  "display":"Clinic Bldg A, Salem Medical Center",
                  "reference":"Location/phcase-smc"
               }
            ],
            "meta":{
               "profile":[
                  "http://fhir.org/guides/argonaut-pd/StructureDefinition/argo-practitionerrole"
               ]
            },
            "organization":{
               "display":"Salem Medical Center",
               "reference":"Organization/phcase-smc"
            },
            "practitioner":{
               "display":"Henry Seven, M.D.",
               "reference":"Practitioner/phcase-mc"
            },
            "resourceType":"PractitionerRole",
            "specialty":[
               {
                  "coding":[
                     {
                        "code":"208D00000X",
                        "display":"General Practice",
                        "system":"http://nucc.org/fhir/codes"
                     }
                  ]
               }
            ],
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-mc</p><p><b>meta</b>: </p><p><b>practitioner</b>: <a href=\"Practitioner-phcase-mc.html\">Henry Seven, M.D.. Generated Summary: id: phcase-mc; 1521001101; Seven Henry </a></p><p><b>organization</b>: <a href=\"Organization/phcase-smc\">Salem Medical Center</a></p><p><b>code</b>: Doctor <span style=\"background: LightGoldenRodYellow\">(Details : {http://hl7.org/fhir/practitioner-role code 'doctor' = 'Doctor', given as 'Doctor'})</span></p><p><b>specialty</b>: General Practice <span style=\"background: LightGoldenRodYellow\">(Details : {http://nucc.org/fhir/codes code '208D00000X' = '208D00000X', given as 'General Practice'})</span></p><p><b>location</b>: <a href=\"Location-phcase-smc.html\">Clinic Bldg A, Salem Medical Center. Generated Summary: id: phcase-smc; status: active; name: Clinic Bldg A, Salem Medical Center; ph: (+1) (555)555-3001, fax: (+1) (555)555-3002, mail@smc.org</a></p><p><b>endpoint</b>: <a href=\"Endpoint/phcase-mcdirect\">henry.seven.MD@direct.smc.org</a></p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      },
      {
         "fullUrl":"http://sqlonfhir-stu3.azurewebsites.net/fhir/ProcedureRequest/phcase-zika",
         "resource":{
            "category":[
               {
                  "coding":[
                     {
                        "code":"103693007",
                        "display":"Diagnostic procedure (procedure)",
                        "system":"http://snomed.info/sct"
                     }
                  ],
                  "text":"Diagnostics Procedure"
               }
            ],
            "code":{
               "coding":[
                  {
                     "code":"80825-3",
                     "display":"Zika virus envelope (E) gene [Presence] in Serum by Probe and target amplification method",
                     "system":"http://loinc.org"
                  }
               ],
               "text":"Zika RT-PCR"
            },
            "id":"phcase-zika",
            "intent":"order",
            "performer":{
               "display":"Acme Labs",
               "reference":"Organization/acme-labs"
            },
            "priority":"asap",
            "resourceType":"ProcedureRequest",
            "status":"completed",
            "subject":{
               "reference":"Patient/phcase-js"
            },
            "text":{
               "div":"<div xmlns=\"http://www.w3.org/1999/xhtml\"><p><b>Generated Narrative with Details</b></p><p><b>id</b>: phcase-zika</p><p><b>status</b>: completed</p><p><b>intent</b>: order</p><p><b>priority</b>: asap</p><p><b>category</b>: Diagnostics Procedure <span style=\"background: LightGoldenRodYellow\">(Details : {SNOMED CT code '103693007' = 'Diagnostic procedure', given as 'Diagnostic procedure (procedure)'})</span></p><p><b>code</b>: Zika RT-PCR <span style=\"background: LightGoldenRodYellow\">(Details : {LOINC code '80825-3' = 'Zika virus envelope (E) gene [Presence] in Serum by Probe and target amplification method', given as 'Zika virus envelope (E) gene [Presence] in Serum by Probe and target amplification method'})</span></p><p><b>subject</b>: <a href=\"Patient-phcase-js.html\">Generated Summary: id: phcase-js; Medical Record Number = 1032702 (USUAL), SSN = 11-00-1234 (USUAL); active; Eve L Everywoman ; ph: 1-(404)555-1212(HOME), eve.everywoman@example.com; gender: female; birthDate: Nov 24, 1974</a></p><p><b>performer</b>: <a href=\"Organization/acme-labs\">Acme Labs</a></p></div>",
               "status":"generated"
            }
         },
         "search":{
            "mode":"include",
            "score":1
         }
      }
   ]
}
~~~
