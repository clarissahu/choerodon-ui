---
order: 9
title:
  zh-CN: 加载
  en-US: Loading
---

## zh-CN

加载。


## en-US

Loading.


````jsx
import { Progress } from 'choerodon-ui';

ReactDOM.render(
  <div>
    <Progress type="loading" size="small" />
    <Progress type="loading" status="success" />
    <Progress type="loading" size="large" status="exception" />
  </div>,
  mountNode
);

````
