# my-google-contacts

After a lot of digging a couldn't find any examples of how to build a google-contacts element. This is what I came up with.

Feel free to fork to impove.

Must have an authiticated user to use.

```<google-sigin client-id="{{clientId}}" scopes="https://www.googleapis.com/auth/contacts"></google-signin><my-google-contacts client-id="{{clientId}}" contacts="{{contacts}}"></my-google-contacts>```
