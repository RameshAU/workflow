## Command to trigger the workflow with repository dispatch - webhook event
> curl -X POST \
>-H "Accept: application/vnd.github+json" \
>-H "Authorization: token <personal access token>" \
>-d '{"event_type": "webhook", "client_payload": {"key": "value"} }' \
>https://api.github.com/repos/RameshAU/workflow/dispatches
