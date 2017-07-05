Admin Restrict Branch
================

Processwire module to restrict site editors to a single branch of the tree.

### Functionality

You can restrict the user to only be able to view and/or edit pages from a specific branch of the page tree.

Restrictions work in the admin list view as well as via the API for front-end editing (works with FREDI, FEEL, and manual API calls).

There are three ways to match users to a branch parent:
* Specified Branch Parent
* Role Name
* Custom PHP code

Name matching can be limited to a specific parent to reduce mis-matches and improve matching efficiency.

Determine whether non-matched users will have access to the entire page tree, or no access at all.

Determine whether to limit editing and list viewing, or just editing.

Specify branch exclusions which will allow for editing of PageTable content housed in external parent branches and some other use cases.

Conditionally prevent admin search from returning restricted pages for things like inserting links to pages via the autocomplete option in CKEditor.

Conditionally modify breadcrumbs to remove pages that are outside the restricted branch.


#### Support forum:
https://processwire.com/talk/topic/11499-admin-restrict-branch/


## License

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.

(See included LICENSE file for full license text.)