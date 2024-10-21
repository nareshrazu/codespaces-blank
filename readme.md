  # AG Grid Integration Guide

## Step 1: Component Usage
**Do not use directly from `app.component.html`. Instead, use it from the routes subcomponent.**

## Step 2: Required Packages
### Install the following packages:
- `ag-grid-angular`
- `ag-grid-community`
- `@angular/cdk`
- `@angular/material`

### CSS Styles
Add the following AG Grid CSS styles to your `angular.json` file under `architect > build > styles`:

```json
"node_modules/ag-grid-community/styles/ag-grid.css",
"node_modules/ag-grid-community/styles/ag-theme-quartz.css"
