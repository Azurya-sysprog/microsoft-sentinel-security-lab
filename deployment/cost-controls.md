# Azure Cost Controls

The lab is designed to remain within an approximate maximum budget of A$20.

## Controls

- Configure a monthly Azure budget of A$20.
- Create alerts at 50%, 75%, 90% and 100%.
- Use a small B-series Windows VM.
- Enable automatic VM shutdown.
- Manually deallocate the VM after each session.
- Collect only the Windows events needed for the project.
- Avoid paid Logic Apps during the initial build.
- Review Azure Cost Management regularly.
- Delete the resource group after completing and documenting the lab.

## Important Note

Stopping Windows inside the operating system might not stop Azure compute charges. The VM should be shown as **Stopped (deallocated)** in the Azure portal.
