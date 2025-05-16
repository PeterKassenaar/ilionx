# ilionx

Slides and sample code on the training Angular Fundamentals, Ilionx, Young Professional Program, Spring 2025.

* See the various slides in the `./slides` directory. 
* This repo will be deleted on 19 June, 2025. Make sure you have a copy before that date.
* General example code: https://github.com/PeterKassenaar/angular-fundamentals


## Links
* More on monorepo structure, NX: https://nx.dev/
* More on Angular: https://angular.dev/
* Please fill in the evaluation: https://globalknowledge.az1.qualtrics.com/jfe/form/SV_2l9xxtKvLOyJCKN?EVENTID=NL242807
* ...

# Examples

We talked about `@HostListener`. You can use this as an example:

```typescript
@HostListener('window:online', ['$event'])
onOnline(event: any) {
    this.bgColor= 'green';
    // Go syncing, show message we are online again
}

@HostListener('window:offline', ['$event'])
onOffline(event: any) {
    this.bgColor= 'red';
    // We are offline, show a message.
}
```
