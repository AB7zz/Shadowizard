# What is this for?

Get the perfect shdows every time 

# Installation

'npm i react-ab7-image --save'

Then...

```
import {shadowizard} from 'react-ab7-image';

shadowizard({
    shadow_type: 'soft',
    padding: false
});
```

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* - hard | soft (Defaults to soft)
* *padding* - true | false (Defaults to false)

# Drawbacks
* *className='shadowizard'* won't work if you're using styled-components to style your <img> tag. For example

```
export const Img = styled.img``
<Img src={src} alt={alt} />
```

# Project isn't complete yet! More change to come very soon
