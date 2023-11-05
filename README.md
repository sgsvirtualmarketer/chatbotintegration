# Virtual Marketer GmbH

## Chat-Bot Integration

To add the Virtual Marketer Chat-Bot to a website, the first step would be to add the core script.
It is found in `chatbot.js`. Include it on the body of your page.

For configuration and initialisation add the following script right after the previous one.
Mandatory parameters are `product`, `apiKey` and `apiUrl`. The first two are provided by our customer service.
The api url is `https://api.virtual-marketer.de/api/ai`.

```
<script type="text/javascript">
    new VmChatBot({
        product:"",
        apiKey:"",
        apiUrl:"",
    });
</script>
```

## Additional Configuration

Add the following variables to the constructor of the VmChatBot instantiation shown above.

### initial text

It is possible to define a initial message, which is displayed when whe chat window opens.

**parameter**: *initText*

**Example**:  `initText:"Hallo ich bin der VirtualMarketer, wie kann ich helfen?\n",`

### top bar name

Also a top bar name can be defined.

**parameter**: *chatTopBarName*

**Example**:  `chatTopBarName:"John Doe",`

### primary color

The primary color is changed via the following parameter.

**parameter**: *chatTopBarName*

**Example**:  `primaryColor:"#233233",`


        
