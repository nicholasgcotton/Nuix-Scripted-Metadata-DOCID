# Scripted Metadata for DOCID
Find the DOCID of the current item using scripted metadata. Intended for reviewing [EDRM](https://edrm.net/resources/frameworks-and-standards/edrm-model/edrm-stages-standards/edrm-processing-standards-guide-version-2/)/Relativity/Concordance formatted data in Nuix Workstation. 

e.g. when you are reviewing data such as "\\Natives\VOL00001\DOCID012345.msg\Re: Contract Dispute" Nuix Workstation will return the email item as the name, that is "Re: Contract Dispute" but it may also be helpful to keep track of the EDRM style DOCID, e.g. DOCID012345.msg.

**Important Note:** Script must be updated with the current DOCID basename to work.

**Instructions**: Open [Scripted Parent DOCID.rb](https://github.com/nicholasgcotton/Nuix-Scripted-Metadata-DOCID/blob/main/Scripted%20Parent%20DOCID.rb) in a text editor and at line 7 change "DOCID0" to reflect the base filename for your document series.

e.g. Change from `document_id_basename = "DOCID0"` to `document_id_basename = "DOCUMENT_ID"`where you file names all start with "DOCUMENT_ID".

For a list of other useful Nuix scripts, see: https://github.com/nicholasgcotton/Nuix-Scripts

Based on [ScriptedField_FullPath.rb](https://github.com/Nuix/Scripted-Metadata-Profile-Fields/blob/master/Ruby/Pathing/ScriptedField_FullPath.rb) from:

[Scripted Metadata Profile Fields](https://github.com/Nuix/Scripted-Metadata-Profile-Fields)
================================

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

View the GitHub project [here](https://github.com/Nuix/Scripted-Metadata-Profile-Fields) or download the latest release [here](https://github.com/Nuix/Scripted-Metadata-Profile-Fields/releases).

# Overview

This repository contains a collection of scripted metadata profile fields.

# Getting Started

## Usage

In Nuix Workstation, create or edit a metadata profile.

![image](https://user-images.githubusercontent.com/11775738/54219737-4d64e680-44ad-11e9-8392-f32606315e1a.png)

To that profile add a "Scripted Metadata" field.

![image](https://user-images.githubusercontent.com/11775738/54219924-8c933780-44ad-11e9-9b1a-13f7b4943124.png)

On the resulting dialog, provide a name for the field and paste the relevant scripted field code into the lower text area.

![image](https://user-images.githubusercontent.com/11775738/54220023-b2b8d780-44ad-11e9-864f-81aed6deb153.png)

# License

```
Original Code Copyright 2020 Nuix

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
