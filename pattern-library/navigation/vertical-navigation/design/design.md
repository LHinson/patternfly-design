Jump to [Primary Navigation](#primary-navigation), [Primary with Secondary Navigation](#primary-with-secondary-navigation), [Primary with Fly Out Secondary Navigation](#primary-with-fly-out-secondary-navigation), [Primary with Tertiary Navigation](#primary-with-tertiary-navigation), or [Responsive States](#responsive-states)

## Primary Navigation
![navigation-primary-callout](img/navigation-primary-callout.png)

1. **Masthead:** See the   [Masthead](https://www.patternfly.org/pattern-library/application-framework/masthead/#_) pattern for more details.
2. **Primary Navigation Icons** (optional): When the primary areas of the UI are easily represented by icons, they may be used in the primary navigation.
3. **Hover**: On hover, the primary navigation item is highlighted.
4. **Selection**: A selected primary navigation item is highlighted and includes a vertical blue line decorator.

## Primary with Secondary Navigation
Secondary navigation is non-persistent, appearing on hover. The secondary navigation is shown in a second column that appears to the right. (See [Secondary Navigation | Responsive State](#secondary-navigation-|-responsive-state) for how the secondary navigation is displayed on small screens.)

![navigation-with-secondary-callout](img/navigation-with-secondary-callout.png)

1. **Label**: The label at the top of the secondary menu mirrors the selected primary category to reinforce the user’s current location.
2. **Selection**: A selected item in the secondary navigation is highlighted.
3. **Hover**: On hover, the secondary navigation is highlighted and underlined.

## Primary with Fly Out Secondary Navigation
Fly out secondary navigation acts the same as the [Primary with Secondary Navigation](#primary-with-secondary-navigation), but provides an option for when a whole column is not needed for the navigation items. This is ideal for a smaller set of secondary navigation throughout the entire application. This should not be mixed with the base [Primary with Secondary Navigation](#primary-with-secondary-navigation). The fly out secondary navigation is shown in a fly out that appears to the right. (See [Secondary Navigation | Responsive State](#secondary-navigation-|-responsive-state) for how the secondary navigation is displayed on small screens. NOTE: This is the same for if you are using the [Primary with Secondary Navigation](#primary-with-secondary-navigation).)

![navigation-with-secondary-callout](img/navigation-with-fly-out-secondary-callout.png)

1. **Selection**: A selected item in the secondary navigation is highlighted.
2. **Hover**: On hover, the secondary navigation is highlighted and underlined.

## Primary with Tertiary Navigation
Tertiary navigation is non-persistent and only appears on hover. The tertiary navigation is shown as a third column that opens to the right.

![navigation-with-tertiary-callout](img/navigation-with-tertiary-callout.png)

1. **Pin Menu**(optional):
  - If the secondary navigation is pinned, the navigation is collapsed to a single column and the secondary navigation is the only menu visible.
  - If the tertiary navigation is pinned, the navigation is collapsed to a single column and the tertiary navigation is the only menu visible.
2. **Label**:
  - The label at the top of the secondary navigation mirrors the selected primary category to reinforce the user’s current location.
  - The label at the top of the tertiary navigation mirrors the selected secondary category to reinforce the user’s current location.
3. **Selection**: A selected item in the tertiary navigation is highlighted.
4. **Hover**: On hover, the tertiary navigation is highlighted and underlined.

## Responsive States
- **Small Screen** (From 768 to 1200px): In all cases, the secondary navigation, if one exists, will replace the primary menu in a one column layout (same interactions as full-width without icons).
- **Mobile** (less than 768 px): Navigation is hidden under “hamburger” icon.

### Primary Navigation | Responsive State

![navigation-vertical-responsive-state-callout](img/navigation-vertical-responsive-callout.png)

1. **Menu Drawer**: When open, the menu appears as a drawer sliding out from the left edge of the viewport. This will overlay content area.
2. **Utility Items**:
  - Once the utility items do not fit in the masthead (on small screens), they will responsively move to rest underneath the main navigation items in the vertical navigation.
  - In any instance that there is an icon present in desktop state with no text label (for example, the help icon), a text label will appear next to that icon in this responsive state.


### Secondary Navigation | Responsive State
![navigation-vertical-secondary-responsive-callout](img/navigation-vertical-secondary-responsive-callout.png)
1. **Back Link**: Clicking the back link restores the primary-level menu.
2. **Back Link** (for Utility Item): The back link for a utility item is formatted differently from the back links for main navigational items.

<!--
### Notification Drawer | Responsive State
This is how the notification drawer looks on small screens. Once a user selects "Notifications" within a small screen's vertical navigation menu, the notification drawer appears in full-width, with a Back Link above it. [See Here](http://www.patternfly.org/pattern-library/communication/notification-drawer/#/api) for specifics about the Notification Drawer.

![navigation-vertical-notifications-responsive-callout](img/navigation-vertical-notifications-responsive-callout.png)

1. **Back Link**: Clicking the back link restores the primary-level menu.
2. **Notification Drawer**: The notification drawer takes the entire screen's width when on small screens.)
-->
