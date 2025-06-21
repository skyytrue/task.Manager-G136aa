<tr th:each="task:${tasks}">
                    <td th:text="${task.name}">
                    </td>
                    <td th:text="${task.description}">
                    </td>
                    <td th:text="${task.deadlineDate}">
                    </td>
                    <td th:text="${task.isCompleted()}">
                    </td>

                    <td class="btn btn-primary btn" style="background-color: #31d2f2; color: white">DETAILS</td>
                </tr>
