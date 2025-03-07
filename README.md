# Flux

Flux is the official UI component library for [Livewire](https://livewire.laravel.com).

You can view the components in action at [https://fluxui.dev](https://fluxui.dev).

## Installation

Run the following command from your project's root directory:

```bash
composer require livewire/flux:v1.0.0-beta.1 --prefer-dist
```

Flux has built-in scripts and styles that are required to use the components. Add the following to your app template's `head` and `body` tags:

```html
<head>
    ...

    @fluxStyles
</head>
<body>
    ...

    @fluxScripts
</body>
```

Flux uses Tailwind CSS for its styles.

To get started quickly, you can include the Tailwind Play CDN in your `head` tag:

```html
<head>
    ...

    <script src="//cdn.tailwindcss.com"></script>

    @fluxStyles
</head>
```

Or, for a more robust setup, you can include Flux's Blade files as part of your build in your Tailwind config's `content` array:

```javascript
module.exports = {
    content: [
        ...,
        "./vendor/livewire/flux-pro/stubs/**/*.blade.php",
        "./vendor/livewire/flux/stubs/**/*.blade.php",
    ],
    ...
}
```

## What's included?

The following components are included in the `livewire/flux` package:
* [Dropdown](https://fluxui.dev/components/dropdown)
* [Icon](https://fluxui.dev/components/icon)

The rest of the Flux components are part of the paid (Pro) tier of Flux.

Purchase a "Pro" license key here: [https://fluxui.dev/pricing](https://fluxui.dev/pricing)
