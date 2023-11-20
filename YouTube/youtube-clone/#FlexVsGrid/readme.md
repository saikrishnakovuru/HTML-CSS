in Grid we define columns and the elements go into those columns.

```java
<div style="
        display: grid;
        grid-template-columns: 100px 1fr;
        margin-top: 15px;">

        <div style="background-color: lightblue;">100px dgfdgdfgdfgg</div>
        <div style="background-color: lightsalmon;">1fr</div>
    </div>
```

In Felx we define the flex style within the component

```java
<div style="
        display: flex;
        flex-direction: row;
        ">

        <div style="
        background-color: lightcoral;
        width: 100px;
        ">div1 test</div>

        <div style="
        background-color: lightgreen;
        flex: 1;
        ">div2
            <p>test</p>
        </div>
    </div>
```