# Start Building Your App

Messaging App guides you throughout building your app, providing the steps and procedure to customize.


**Contents discussed in this section:**
* How to add new Component?
* How to add new StyleSheet?

### How to add new component

* Create a new folder, say ``` newComponent ``` and place it under ``` /src``` .
* Create a new file ``` index.js``` , within this folder.
* Name the class same as that of folder name.

```
class NewComponent extends Component {
    ...
}
```
### How to add new styleSheet

Create a new file ``` styles.js``` , place it under ```/src/newComponent```.
```import``` newly created StyleSheet into the Component.
```
import styles from './styles';
class NewComponent extends Component {
    ...
}
```
