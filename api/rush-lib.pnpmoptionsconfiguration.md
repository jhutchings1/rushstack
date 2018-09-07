[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [PnpmOptionsConfiguration](./rush-lib.pnpmoptionsconfiguration.md)

# PnpmOptionsConfiguration class

Options that are only used when the PNPM package manager is selected.

## Properties

|  Property | Access Modifier | Type | Description |
|  --- | --- | --- | --- |
|  [`strictPeerDependencies`](./rush-lib.pnpmoptionsconfiguration.strictpeerdependencies.md) |  | `boolean` | If true, then Rush will add the "--strict-peer-dependencies" option when invoking PNPM. This causes "rush install" to fail if there are unsatisfied peer dependencies, which is an invalid state that can cause build failures or incompatible dependency versions. (For historical reasons, JavaScript package managers generally do not treat this invalid state as an error.)<p/>The default value is false. (For now.) |

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the PnpmOptionsConfiguration class.

It is valid to define these options in rush.json even if the PNPM package manager is not being used.