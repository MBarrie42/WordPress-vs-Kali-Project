# Project 7 - WordPress Pentesting

Time spent: 10 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

### 1. (Required) Authenticated Stored Cross-Site Scripting via Image Filename
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.13
  - [ ] GIF Walkthrough: 
     <img src="https://github.com/MBarrie42/Week-7-WordPress-vs-Kali/blob/main/XSS%20Image.gif" width="800">
  - [ ] Steps to recreate: Upload a post with the image url as a XSS exploit. This is where the Javascript is inserted.
  - [ ] Affected source code:
    - [Link 1] https://sumofpwn.nl/advisory/2016/persistent_cross_site_scripting_vulnerability_in_wordpress_due_to_unsafe_processing_of_file_names.html
### 2. (Required) Unauthenticated Stored Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.13
  - [ ] GIF Walkthrough: 
     <img src="https://github.com/MBarrie42/Week-7-WordPress-vs-Kali/blob/main/ONMOUSEOVER.gif" width="800">
  - [ ] Steps to recreate: Create a post with the OnMouseOver() XSS script
  - [ ] Affected source code:
    - [Link 1]
### 3. (Required) User Enumeration
  - [ ] Summary: 
    - Vulnerability types:Enumeration
    - Tested in version: 4.2  
    - Fixed in version: 4.2.13
  - [ ] GIF Walkthrough: 
    <img src="https://github.com/MBarrie42/Week-7-WordPress-vs-Kali/blob/main/User.gif" width="800">
  - [ ] Steps to recreate: Login shows a user exists or not. This is a security issue
  - [ ] Affected source code:
    - [Link 1]
### 4. (Optional) IFrame Script
  - [ ] Summary: 
    - Vulnerability types: 4.2 
    - Tested in version: 4.2.13
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
     <img src="https://github.com/MBarrie42/Week-7-WordPress-vs-Kali/blob/main/Iframe.gif" width="800">
  - [ ] Steps to recreate: Create a new post with a IFrame XSS Script. This promts an alert
  - [ ] Affected source code:
    - [Link 1]
### 5. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
