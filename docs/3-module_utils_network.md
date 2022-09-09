# Module Utils Network

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-module_utils.network.pfsense.pfsense.xml_find-start--->
## module_utils.network.pfsense.pfsense.xml_find

<!---Documatic-section-xml_find-start--->
<!---Documatic-block-module_utils.network.pfsense.pfsense.xml_find-start--->
<details>
	<summary><code>module_utils.network.pfsense.pfsense.xml_find</code> code snippet</summary>

```python
def xml_find(node, elt):
    res = node.find(elt)
    if res is None:
        res = ET.Element('')
        res.text = ''
    return res
```
</details>
<!---Documatic-block-module_utils.network.pfsense.pfsense.xml_find-end--->
<!---Documatic-section-xml_find-end--->

# #
<!---Documatic-section-module_utils.network.pfsense.pfsense.xml_find-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)