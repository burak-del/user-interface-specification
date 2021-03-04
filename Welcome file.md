<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome file</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li><a href="#user-interface-specification-document-for-user-management-screen">User Interface Specification Document For User Management Screen</a>
<ul>
<li><a href="#pages">Pages</a></li>
<li><a href="#uml-diagrams">UML diagrams</a></li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <h1 id="user-interface-specification-document-for-user-management-screen">User Interface Specification Document For User Management Screen</h1>
<p><img src="https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T1RGZ5H7YQMWKPQXFLFIUG5UQ1/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015" alt="enter image description here"></p>
<h2 id="pages">Pages</h2>
<ul>
<li>User list Page
<ul>
<li>Simple button on the top of the page with functionality of redirecting user to New User Page.</li>
<li>Checkbox on the top with functionality of showing/Hiding the disabled user on the datatable.</li>
<li>4 columns datatable on the middle part of the page. Each column can be sorted or filtered by the user.</li>
</ul>
</li>
<li>New User Page
<ul>
<li>Button on the top of the page with functionality of saving new user.</li>
<li>Header with name of “New User”</li>
<li>Textbox for the Username, Display Name.</li>
<li>Textbox for phone area with format of (0xxx) xxx xxxx</li>
<li>Textbox for email area.</li>
<li>Listbox for User Roles. User roles needs to be defined. According to these roles user can be guest, admin or SuperAdmin and have permissions to do actions.</li>
<li>Checkbox for the user’s enabled status. User can be disabled or enabled.</li>
</ul>
</li>
</ul>
<h2 id="uml-diagrams">UML diagrams</h2>
<p>Behavior of the pages:</p>
<div class="mermaid"><svg xmlns="http://www.w3.org/2000/svg" id="mermaid-svg-k84TmxZ3PpTvGosz" width="100%" style="max-width: 391.515625px;" viewBox="0 0 391.515625 88"><g transform="translate(-12, -12)"><g class="output"><g class="clusters"></g><g class="edgePaths"><g class="edgePath" style="opacity: 1;"><path class="path" d="M120.8125,46.6463283958399L194.3515625,33L267.890625,45.31437347136113" marker-end="url(#arrowhead1303)" style="fill:none"></path><defs><marker id="arrowhead1303" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g><g class="edgePath" style="opacity: 1;"><path class="path" d="M267.890625,66.68562652863888L194.3515625,79L120.8125,65.3536716041601" marker-end="url(#arrowhead1304)" style="fill:none"></path><defs><marker id="arrowhead1304" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g></g><g class="edgeLabels"><g class="edgeLabel" transform="translate(194.3515625,33)" style="opacity: 1;"><g transform="translate(-34.796875,-13)" class="label"><foreignObject width="69.59375" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel">New User</span></div></foreignObject></g></g><g class="edgeLabel" transform="translate(194.3515625,79)" style="opacity: 1;"><g transform="translate(-48.5390625,-13)" class="label"><foreignObject width="97.078125" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel">User Creation</span></div></foreignObject></g></g></g><g class="nodes"><g class="node" id="A" transform="translate(70.40625,56)" style="opacity: 1;"><rect rx="5" ry="5" x="-50.40625" y="-23" width="100.8125" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-40.40625,-13)"><foreignObject width="80.8125" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Round Rect</div></foreignObject></g></g></g><g class="node" id="B" transform="translate(331.703125,56)" style="opacity: 1;"><rect rx="0" ry="0" x="-63.8125" y="-23" width="127.625" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-53.8125,-13)"><foreignObject width="107.625" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">New User Page</div></foreignObject></g></g></g></g></g></g></svg></div>

    </div>
  </div>
</body>

</html>
