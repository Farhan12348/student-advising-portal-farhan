# Student Advising Portal (student-advising-portal)

Mobile Advising Portal for School

View the deployment [here](https://gonana-o.web.app/).

## Install the dependencies

```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)

```bash
quasar dev
```

### Lint the files

```bash
yarn lint
# or
npm run lint
```

### Format the files

```bash
yarn format
# or
npm run format
```

### Build the app for production

```bash
quasar build
```

### Customize the configuration

See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-vite/quasar-config-js).

## Architecture Components

### Entities

Definition of all project entities

### UI (User Interface)

Categorized as follows

- **Components** : Reusable Components
- **Dialogs**: Reusable Callable Dialogs
- **Pages**: Application Pages
- **Layouts**: Screen Layouts
- **Routes** : Route configurations

### Workflows

Reusable Business Logics

### Stores

Local State Management

To generate new store file execute

```bash
quasar new store [Storename]
```

Example:

```bash
quasar new store schedules.store
```

Then edit the generated file by replacing all counter related to context of your store

### Services

Access point to External Services
