A simple checkbox form object for Angular 2+. Uses FontAwesome.

Usage:

<checkbox
    [size]="1"
    [value]="false"
    [label]="Click me!"
    (change)="doStuff($event.value);">
</checkbox>

It can also be used as a FormBuilder form element.
