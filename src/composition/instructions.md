Complete **2** simple classes. A **University** class and a **Department** class.


These classes will have a **composition** form of the **association** relationship.That is, a **Department does not exist without a University**. 

The **University** class should have a **String name**. This **name** should be set by the **constructor**. The **University** class should store an **ArrrayList** of **Departments**. This list should start out as **empty**.  

The following two portions of code are reminders of how to import the Java ArrayList, and how to create a new empty ArrayList to store a certain type of object.


```
import java.util.ArrayList;


ArrayList<ObjectName> list_name = new ArrayList<>();
```

For the **University** class please design one mutator 

1. **addDepartment(String name)**, that lets us **add** a new **Department** to a **University**.

The following portion of code is a reminder of how to add an object to an ArrayList;

```
list_name.add(object); 
```

For the **University** class please design two accessors

1. **getName** returns the **String** name of the **University**
2. **getDepartments** returns the **ArrayList<Department>** from the **University**

The **Department** class should have a **String name** and a **integer size** set by the **constructor**.Please design two accessors

3. **getName** returns the **String** name of the **Department** 
4. **getSize** returns the **integer** size from the **Department**