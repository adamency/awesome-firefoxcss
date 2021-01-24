## Donations

Hello, I work on this project to aggregate knowledge on Firefox CSS customization configuration.

If my work helped you, please consider chipping in at: https://www.patreon.com/adamency

# awesome-firefoxcss

## Enable CSS Customization



## Configuration

### Extensions

#### Multi-Account Containers

- Customize container colors:

In `userChrome.css` - [Source](https://github.com/mozilla/multi-account-containers/issues/391#issuecomment-368238595)
```
[data-identity-color="<base_color>"] {
  --identity-tab-color: #<hex_code> !important;
  --identity-icon-color: #<hex_code> !important;
}
```

<base_color> can be: `red`, ...

