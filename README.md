# discord-ui

Status: in development

## TODO

- [x] get theme variables (colours)
- [ ] list all components
- [ ] get css for each component

## Theme Variables

### Dark

```css
.theme-dark {
    --header-primary: #fff;
    --header-secondary: #b9bbbe;
    --text-normal: #dcddde;
    --text-muted: #72767d;
    --text-link: #00b0f4;
    --channels-default: #8e9297;
    --interactive-normal: #b9bbbe;
    --interactive-hover: #dcddde;
    --interactive-active: #fff;
    --interactive-muted: #4f545c;
    --background-primary: #36393f;
    --background-secondary: #2f3136;
    --background-secondary-alt: #292b2f;
    --background-tertiary: #202225;
    --background-accent: #4f545c;
    --background-floating: #18191c;
    --background-mobile-primary: #36393f;
    --background-mobile-secondary: #2f3136;
    --background-modifier-hover: rgba(79,84,92,0.16);
    --background-modifier-active: rgba(79,84,92,0.24);
    --background-modifier-selected: rgba(79,84,92,0.32);
    --background-modifier-accent: hsla(0,0%,100%,0.06);
    --background-mentioned: rgba(250,166,26,0.05);
    --background-mentioned-hover: rgba(250,166,26,0.08);
    --background-message-hover: rgba(4,4,5,0.07);
    --elevation-stroke: 0 0 0 1px rgba(4,4,5,0.15);
    --elevation-low: 0 1px 0 rgba(4,4,5,0.2),0 1.5px 0 rgba(6,6,7,0.05),0 2px 0 rgba(4,4,5,0.05);
    --elevation-medium: 0 4px 4px rgba(0,0,0,0.16);
    --elevation-high: 0 8px 16px rgba(0,0,0,0.24);
    --logo-primary: #fff;
    --guild-header-text-shadow: 0 1px 1px rgba(0,0,0,0.4);
    --channeltextarea-background: #40444b;
    --activity-card-background: #202225;
    --textbox-markdown-syntax: #8e9297;
}
```

### Light

```css
.theme-light {
    --header-primary: #060607;
    --header-secondary: #4f5660;
    --text-normal: #2e3338;
    --text-muted: #747f8d;
    --text-link: #0067e0;
    --channels-default: #6a7480;
    --interactive-normal: #4f5660;
    --interactive-hover: #2e3338;
    --interactive-active: #060607;
    --interactive-muted: #c7ccd1;
    --background-primary: #fff;
    --background-secondary: #f2f3f5;
    --background-secondary-alt: #ebedef;
    --background-tertiary: #e3e5e8;
    --background-accent: #747f8d;
    --background-floating: #fff;
    --background-mobile-primary: #f8f9f9;
    --background-mobile-secondary: #fff;
    --background-modifier-hover: rgba(116,127,141,0.08);
    --background-modifier-active: rgba(116,127,141,0.16);
    --background-modifier-selected: rgba(116,127,141,0.24);
    --background-modifier-accent: rgba(6,6,7,0.08);
    --background-mentioned: rgba(250,166,26,0.1);
    --background-mentioned-hover: rgba(250,166,26,0.2);
    --background-message-hover: rgba(6,6,7,0.02);
    --elevation-stroke: 0 0 0 1px rgba(6,6,7,0.08);
    --elevation-low: 0 1px 0 rgba(6,6,7,0.1),0 1.5px 0 rgba(6,6,7,0.025),0 2px 0 rgba(6,6,7,0.025);
    --elevation-medium: 0 4px 4px rgba(0,0,0,0.08);
    --elevation-high: 0 8px 16px rgba(0,0,0,0.16);
    --logo-primary: #7289da;
    --guild-header-text-shadow: 0 1px 1px hsla(0,0%,100%,0.4);
    --channeltextarea-background: #ebedef;
    --activity-card-background: #fff;
    --textbox-markdown-syntax: #6a7480;
}
```

## Components

### Interactions
- Button
- Chip
- Input
- Dropdown
- Select

### Navigation
- Navbar
- Sidebar
- Toolbar

### Layout
- Scroller
- Divider

### Content
- Mention
- List
- ListItem
- Icon
- Emoji
