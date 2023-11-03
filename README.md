<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE mapper PUBLIC "-//mybatis.org//DTD Mapper 3.0//EN" "http://mybatis.org/dtd/mybatis-3-mapper.dtd">

<mapper namespace="www.bejson.com.dao.UserInfoDao">

    <!-- 可根据自己的需求，是否要使用 -->
    <resultMap type="www.bejson.com.entity.UserInfoEntity" id="UserInfoMap">
                <result property="userId" column="userId"/>
                <result property="userName" column="userName"/>
                <result property="status" column="status"/>
                <result property="createTime" column="createTime"/>
    </resultMap>

</mapper># New-repository
New repository
