# YAML Tutorial

## The Basics

YAML Ain't Markup Language ([YAML](http://yaml.org) is a serialization language and is a subset of JSON. 

All YAML files start with three dashes 

```
--- 
```

### Comments 

begin with a pound sign. They can appear in line. 

``` yaml
---
# this is a YAML comment
foo: bar # this is an inline comment
```
### Structure

YAML documents are primarily composed of key-value pairs. Key value pairs supported are: **strings, floats, booleans, arrays, integers and dictionaries**. Strings can be enclosed in single, double or no quotes at all. YAML recognizes unquoted numerals as integers or floating point. YAML supports the nesting of key-values and the mixing of data types.

```yaml
--- 

# Key-value pairs with different data types

mystring: "This is a string example." # string
myunquotedstring: this is an unquoted string example. #string
pi: 3.14 # float 
myboolean: true #boolean
myinteger: 4 # integer

# array example with 2 space indentation (tabs are not allowed)
singers:
  - Michael Jackson
  - Prince
  - Elvis
  
# dictionary example 

mydictionary:
  mynestedarray: three
    array-item1: 1
    array-item2: 2
    array-item3: three
    array-item4:
      count:5
      location:"somewhere in the world"
    array-item5: 5
    

```


## Resources
[YAML Lint](http://www.yamllint.com/)



