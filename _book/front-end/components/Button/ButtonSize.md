#### Button Size

Want to have buttons of fancy size?<br />
Include the following props with your <code>Button</code>.
* <code>small</code>: for small size button.
* <code>large</code>: for large size button.

<br />
    <table>
      <thead>
        <tr style="border-style: hidden;">
          <td style="border-style: hidden;padding-left: 50px"><i class="fa fa-apple fa-5x" style="color: grey"></i>   <span style="color: grey;font-weight: 500">iOS</span></td>
          <td style="padding-left: 50px"><i class="fa fa-android fa-5x" style="color: grey"></i>   <span style="color: grey;font-weight: 500">Android</span></td>
        </tr>
      </thead>
      <thead>
        <tr style="border-style: hidden">
          <th style="border-style: hidden"><div style="background: url(../../assets/iphone.png) no-repeat; padding: 63px 20px 100px 18px; width: 292px"><img src="{{('../../assets/ios/components/button-size.png')}}" alt="" /></div></th>
          <th><div style="background: url(../../assets/android.png) no-repeat; padding: 45px 118px 68px 0px; background-size: 292px 576px;"><img height="490px" width="266px" src="{{('../../assets/android/components/button-size.png')}}" alt="" /></div></th>
        </tr>
      </thead>
    </table>
*Syntax*

<pre class="line-numbers"><code class="language-jsx">import React, { Component } from 'react';
import { Container, Content, Button, Text } from 'native-base/ui';
​
export default class ButtonSizeExample extends Component {
    render() {
        return (
            &lt;Container>
                &lt;Content>
                    //Small size button
                    &lt;Button small primary>
                      &lt;Text> Primary &lt;/Text>
                    &lt;/Button>

                    //Regular size button
                    &lt;Button success>
                      &lt;Text> Success &lt;/Text>
                    &lt;/Button>

                    //Large size button
                    &lt;Button large info>
                      &lt;Text> Info &lt;/Text>
                    &lt;/Button>
                &lt;/Content>
            &lt;/Container>
        );
    }
}</code></pre>
