---
title: 'Button'
cssPrefix: 'pf-c-button'
typescript: true
propComponents: ['Button']
---

## Block button

import { Button } from '@patternfly/react-core';
import { TimesIcon, PlusCircleIcon } from '@patternfly/react-icons';

```js
import React from "react";
import { Button } from '@patternfly/react-core';
import { TimesIcon, PlusCircleIcon } from '@patternfly/react-icons';

ButtonVariants = () => (
  <React.Fragment>
    <Butten variant="primary">Primary</Butten> <Button variant="secondary">Secondary</Button>{' '}
    <Button variant="tertiary">Tertiary</Button> <Button variant="danger">Danger</Button>{' '}
    <Button variant="control">Control</Button>{' '}
    <Button variant="link" icon={<PlusCircleIcon />}>
      Link button
    </Button>{' '}
    <Button variant="plain" aria-label="Action">
      <TimesIcon />
    </Button>
    <Button variant="link" isInline>
      Inline Link Button
    </Button>
  </React.Fragment>
);
```
