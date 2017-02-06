#### Capitalize Button Text

To have Button text rendered with uppercase, include <code>capitalize</code> prop.<br />
**Note:** This prop is applicable only for Android.

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
          <th style="border-style: hidden"><div style="background: url(../../assets/iphone.png) no-repeat; padding: 63px 20px 100px 18px; width: 292px"><img src="{{('../../assets/ios/components/capitalize-button-text.png')}}" alt="" /></div></th>
          <th><div style="background: url(../../assets/android.png) no-repeat; padding: 45px 118px 68px 0px; background-size: 292px 576px;"><img height="490px" width="266px" src="{{('../../assets/android/components/capitalize-button-text.png')}}" alt="" /></div></th>
        </tr>
      </thead>
    </table>
*Syntax*

<pre class="line-numbers"><code class="language-jsx">import React, { Component } from 'react';
import { Container, Content, Button, Text } from 'native-base/ui';
​
export default class CapitalizeButtonTextExample extends Component {
    render() {
        return (
            &lt;Container>
                &lt;Content>
                    // NativeBase default style
                    &lt;Button>
                      &lt;Text> Click Me! &lt;/Text>
                    &lt;/Button>

                    // Using capitalize prop
                    &lt;Button capitalize>
                      &lt;Text> Click Me! &lt;/Text>
                    &lt;/Button>
                &lt;/Content>
            &lt;/Container>
        );
    }
}</code></pre>
