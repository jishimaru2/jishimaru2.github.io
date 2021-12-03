---
layout: essay
type: essay
title: Follow a Format!
# All dates must be YYYY-MM-DD format!
date: 2021-12-02
labels:
  - Design Pattern
---

I view design patterns as a template used in software development that is used to solve the problem at hand. Similar to this I think the use of templates are very useful in helping follow a format to ease the workload upon us. One that comes to mind is during the creation of documents whether that be writing a letter, taking notes, constructing an essay, etc. Since we were able to grasp a keyboard I feel that we were programmed to follow a format to make life easier and optimize our workflow. We’ve all heard the following sentence “Times New Roman, Size 12 font, and double spaced!”. I don’t think this is a quicidence as following templates not only helps the writer be able to write efficiently but it also helps the reader understand the content at a clear and concise level. This is also why I believe that having a template to follow is extremely important. 

#### Use of Design Pattern in Final Project

With this design pattern is another template that I use when creating. During my software development for my final project the main one that I recall using was Singleton.

Singleton encapsulates a collection where the instance of a class can be used to manipulate by the import of that variable from that file. In my case for the final project I viewed the singleton to be the most important as it was the most important design pattern we had used. As we had multiple collections which we had to access and it seemed like in our project singleton's were being used everywhere. One singleton we had was the Profiles Collection which contained schema which was encapsulated by Profile where then it was used by importing Profile to access the data. 

#### Single instance of the Profile Collection
```
export const Profile = new ProfilesCollection();
```
#### Using Profile 
```
import { Profile } from '../../api/profile/Profile';
```

