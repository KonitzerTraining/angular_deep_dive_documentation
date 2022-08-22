# Interne und Externe Route Definitionen

## Routen zwischen Komponenten

## Routen zu externen Seiten

```typescript
// Some code
import { Component, OnInit } from "@angular/core";

@Component({
  selector: "redirect",
  template: "redirecting...",
})
export class RedirectComponent implements OnInit {
  constructor() {}

  ngOnInit() {
    window.location.href = "http://www.example.com";
  }
}
```

{% embed url="https://gist.github.com/KonitzerTraining/edbd0fb238b18ab125888bb657694817.js" %}

{% embed url="https://codepen.io/konitzertraining/pen/bGvZNyJ" %}

