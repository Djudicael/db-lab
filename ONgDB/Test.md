# Create a node

````
create(n)
````
# See the node

````
match(n) return n
````

# Create a node with a label

````
create(n:employee)

create(d:employee) return d
````

# Create multinode same query

````
create(e:employee),(d:department)return e,d
````
# Create node with multiple labels

````
create(e:employee:professor) return e
````

# Create node with properties

````
create(e:employee{name:'Judicaël',address:'Saint-Herblain'}) return e
````

# Create multiple node with properties

````
create(e:employee{name:'John'}),(d:department{name:'scope'}) return e,d
````


# Match clause

Its like SELET in sql
