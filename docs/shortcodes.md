# Shortcodes

## Buttons

!!! info "Info"
    You can enter following attributes in button shortcode.
<strong>link</strong> : URL you want to used for the button
<br/><strong>target</strong> : _blank | _self | _parent | _top
<br/><strong>type</strong> : info | success | warning | danger | Leave empty for default style.
<br/><strong>size</strong> : sm | lg | Leave empty for default style.
  
    [inspiry_button link="your_link_here"]Button[/inspiry_button]
    
    [inspiry_button link="your_link_here" type="info"]Button[/inspiry_button]
    
    [inspiry_button link="your_link_here" type="success"]Button[/inspiry_button]
    
    [inspiry_button link="your_link_here" type="warning"]Button[/inspiry_button]
    
    [inspiry_button link="your_link_here" type="danger"]Button[/inspiry_button]
    
<img src="../img/misc/buttons.png" alt="">
    
<div class="section-separator"></div>

## Lists

### Bullet List Style
  
    [inspiry_list]
    <ul>
        <li>List item one</li>
        <li>List item two</li>
        <li>List item three</li>
        <li>List item five</li>
    </ul>
    [/inspiry_list]
    
<img src="../img/misc/list-1.png" alt="">
    
### Arrow List Style 
    
    [inspiry_list type="arrow"]
     <ul>
         <li>List item one</li>
         <li>List item two</li>
         <li>List item three</li>
         <li>List item five</li>
     </ul>
    [/inspiry_list]

<img src="../img/misc/list-2.png" alt="">

<div class="section-separator"></div>

## Columns

### Single Column

    [columns]
    [single_column]This is One Half Column[/single_column]
    [/columns]

### 1/2 Columns

    [columns]
    [one_half]This is One Half Column[/one_half]
    [one_half]This is One Half Column[/one_half]
    [/columns]

### 1/3 Columns

    [columns]
    [one_third]This is One Third Column[/one_third]
    [one_third]This is One Third Column[/one_third]
    [one_third]This is One Third Column[/one_third]
    [/columns]

### 1/4 Columns

    [columns]
    [one_fourth]This is One Fourth Column[/one_fourth]
    [one_fourth]This is One Fourth Column[/one_fourth]
    [one_fourth]This is One Fourth Column[/one_fourth]
    [one_fourth]This is One Fourth Column[/one_fourth]
    [/columns]

### 1/6 Columns

    [columns]
    [one_sixth]This is One Sixth Column[/one_sixth]
    [one_sixth]This is One Sixth Column[/one_sixth]
    [one_sixth]This is One Sixth Column[/one_sixth]
    [one_sixth]This is One Sixth Column[/one_sixth]
    [one_sixth]This is One Sixth Column[/one_sixth]
    [one_sixth]This is One Sixth Column[/one_sixth]
    [/columns]

### 3/4 Columns

    [columns]
    [three_fourth]This is Third-Fourth Column[/three_fourth]
    [/columns]