buildAndPackageLib("kson"
	COMPONENT "kson"
	DESCRIPTION "${PROJECT_DESCRIPTION}\n\nA small and lightweight JSON parser."
	CMAKE_EXPORT_NAMESPACE "${PROJECT_NAME}"
	PUBLIC_INCLUDES "${CMAKE_CURRENT_LIST_DIR}"
	INSTALL_INCLUDE_DIR "${CMAKE_INSTALL_INCLUDEDIR}/${PROJECT_NAME}"
)
