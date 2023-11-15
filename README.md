# Task Management using REST API

A simple task management application using Spring boot that performs CRUD operations using REST controller

## CRUD 
CRUD stands for Create, Read, Update and Delete. As the name suggests it performs the related operations on the relational database and mapped to standard HTTP method.
<!-- 
## Operations

### Get All Tasks
```
    @GetMapping("/alltasks")
    public List<Task> getAllTasks() {
        return taskService.getAllList();
    }
```
Get all tasks stored by a Get Mapping method
![all tasks](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/allTasks.png)


### Get Task by ID
```
    @RequestMapping("/getTask")
    public Task getTask(@RequestParam("id") Integer id) {
        return taskService.getTask(id);
    }
```
Get a task by an id parameter
![id](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/taskById.png)

### Save a Task
```
    @PostMapping(value="/saveTask")
    public void createTask(@RequestBody Task task) {
        taskService.createTask(task);
    }
```
The save task method uses post mapping. It gets a task body as an input and stores into the DB.
![save task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/saveTask.png)
After saving new Task
![new save task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/newAllTasks.png)

### Change Status
```
    @RequestMapping(value = "/changeStatus", method = RequestMethod.PUT)
    public void updateStatus(@RequestParam("id") Integer id,  @RequestBody Task task ) { 
        taskService.updateStatus(id, task);
    }
```
The Change status method uses PUT method to update the status of the task by getting id as a parameters and the whole task body as input.
![Change Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/changeStatus.png)
Before Change Task
![Before Change Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/beforeChange.png)
After Change Task
![After Change Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/afterChange.png)


### Delete Task
```
    @DeleteMapping(value = "/deleteTask")
    public void deleteTask(@RequestParam("id") Integer id) { 
        taskService.deleteTask(id);
    }
```
This deletes the entire task using the delete mapping
![Delete Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/deleteTask.png)
Before delete Task
![Before delete Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/beforeDelete.png)
<<<<<<< HEAD
After delete Task
![After Delete Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/afterDelete.png)
=======
![After Delete Task](https://github.com/ptech12/taskmgmt/blob/master/src/imgs/afterDelete.png) -->
>>>>>>> 1734de6 (Modified for master)
