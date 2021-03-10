# Adding a New Member to the Crossplane Org

For new members to be added to the Crossplane Org, the candidate must open an
issue using the the [New Member
template](../.github/ISSUE_TEMPLATE/new-member.md) after they have spoken to two
current Org members who have agreed to sponsor their membership request.

After the issue has been opened, each sponsor must comment with a `+1`
indicating they agree to sponsor the membership request. When both members have
commented, either of them, or any other Org member, may open a pull request to
the [crossplane/org](https://github.com/crossplane/org) repository, adding that
member to the
[config/members-crossplane.yaml](../config/members-crossplane.yaml) file.

The pull request must be approved and merged by a member of the [Crossplane
steering
committee](https://github.com/crossplane/crossplane/blob/master/GOVERNANCE.md#steering-committee),
at which point the CI GitHub actions on the repo will automatically invite the
user to be a member in the Org.
