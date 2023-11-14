# Task Management using REST API

A simple task management application using Spring boot that performs CRUD operations using REST controller

## CRUD 
CRUD stands for Create, Read, Update and Delete. As the name suggests it performs the related operations on the relational database and mapped to standard HTTP method.

### Operations
```
    @GetMapping("/alltasks")
    public List<Task> getAllTasks() {
        return taskService.getAllList();
    }
```
![all tasks](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/allTasks.png)


```
    @RequestMapping("/getTask")
    public Task getTask(@RequestParam("id") Integer id) {
        return taskService.getTask(id);
    }
```
img


