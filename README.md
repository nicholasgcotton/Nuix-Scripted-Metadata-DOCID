# Scripted Metadata for DOCID
Find the DOCID of the current item using scripted metadata. Intended for reviewing EDRM/Relativity/Concordance formatted data in Nuix Workstation. 

e.g. when you are reviewing data such as "\\Natives\VOL00001\DOCID12345.msg\Re: Contract Dispute" Nuix Workstation will return the email item as the name, that is "Re: Contract Dispute" but it may also be helpful to keep track of the EDRM style DOCID, e.g. DOCID12345.msg.

Script must be updated with the current DOCID basename to work.

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
