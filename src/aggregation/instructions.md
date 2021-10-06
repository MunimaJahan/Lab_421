 Complete **2** simple classes. 
A **Lab** class and a **Student** class.


These classes will have an **aggregation** form of the **association** relationship.


That is, a **Student can exist without a Lab**. The **Student** class should have a **String name** and **integer id**. This **name** and **id** should be set by the **constructor**.  


Please design three accessors for the **Student** class.

1. **getName** returns the **String name**
2. **getId** returns the **integer id**
3. **toString** returns **String** of form **"<name> <id>"**

The **Lab** class should store an **ArrrayList** of **Students**. This list should start out as **empty.** The **Lab** should also store an **integer** for a **lecture** (session) and an **integer** lab **id**. 

Please design four accessors for the **Lab** class.

4. **getLecture** returns the **integer lecutre** of the **Lab**
5. **getId** returns the **integer id** from the **Lab**
6. **getStudents** returns the **ArrayList<Student> students** from the **Lab**
7. **toString** return **String** of form 

```
**"<lecture>-<id>\n<student toString>\n<student toString>\n"**
```

Please design the following mutator for the **Lab** class

1. **addStudent** that stores a **Student student** in the Lab