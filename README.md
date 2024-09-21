# Day 5 challenge of 50 days HTML Learning ✨💥
## TOPIC :
- **Day 5:** Lists Unordered lists with ul and li .Ordered lists with ol and li.Nesting lists.

# Lists in HTML


## Unordered Lists with `ul` and `li`

- **Unordered lists :** are used to group a collection of items that do not have a specific order or sequence. They are defined using the `<ul>` element, and each item in the list is defined using the `<li>` element.

### Example :
          
    <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ul>

- **Output :**

       • Item 1

       • Item 2

       • Item 3

- **Ordered Lists :** with `<ol>` and `<li>`
Ordered lists are used to group a collection of items that have a specific order or sequence. They are defined using the `<ol>` element, and each item in the list is defined using the `<li>` element.

### Example :
    <ol>
       <li>Item 1</li>
       <li>Item 2</li>
       <li>Item 3</li>
    </ol>

- **Output :**

       Item 1

       Item 2

      Item 3

- **Nesting Lists :**
Lists can be nested inside each other to create a hierarchical structure.

### Example :

    <ul>
       <li>Item 1</li>
       <li>Item 2
    <ul>
      <li>Sub-item 1</li>
      <li>Sub-item 2</li>
    </ul>
    </li>
      <li>Item 3</li>
    </ul>

- **Output :**

             • Item 1

             • Item 2

           • Sub-item

             1 • Sub-item

             2 • Item 3

- **Description List :**
  A description list (or definition list, as it was called before HTML5) can be created with the `dl`
It consists of name-value groups, where the name is given in the `dt` element, and the value is given in the `dd` element.

### Example :
    <dl>
      <dt>name 1</dt>
      <dd>value for 1</dd>
    <dt>name 2</dt>
      <dd>value for 2</dd>
    </dl>

- **Output :**

            name 1

           value for 1

         name 2

           value for 2


- **A name-value group:** It can have more than one name and/or more than one value (which represent alternatives):

### Example :


        <dl>
           <dt>name 1</dt>
           <dt>name 2</dt>
          <dd>value for 1 and 2</dd>
           <dt>name 3</dt>
           <dd>value for 3</dd>
           <dd>value for 3</dd>
        </dl>


- **Output :**

         name 1
         name 2
              value for 1 and 2
         name 3
              value for 3
              value for 3

